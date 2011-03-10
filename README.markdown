These are deploy.yml files for whiskey_disk deployments.

Note that whiskey_disk can read a configuration .yml file directly over the
web, so I can do, e.g.,:

    % wd deploy --to=dotfiles:`hostname` --path=https://github.com/rick/deploy/raw/master/deploy.yml

On any machine that wants its dotfiles, and get them updated automatically.

Bonus points for using a config repository to protect AWS keys, passwords, etc.
