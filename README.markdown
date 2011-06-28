These are deploy.yml files for whiskey_disk deployments.

Note that whiskey_disk can read a deployment configuration YAML file directly over the web, so I can do, e.g.,:

    % wd deploy --to=dotfiles:`hostname` --path=https://github.com/rick/deploy/raw/master/dotfiles.yml

On any machine that wants its dotfiles, and get them updated automatically.

Bonus points for using a config repository to protect AWS keys, passwords, etc.

More information:

 * whiskey\_disk: for embarrassingly fast deployments: [https://github.com/flogic/whiskey_disk](https://github.com/flogic/whiskey_disk)

 * my dotfiles repo:  [https://github.com/rick/dotfiles](https://github.com/rick/dotfiles)
