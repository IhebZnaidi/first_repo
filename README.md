# first_repo
README
hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git init
Reinitialized existing Git repository in C:/Users/hp/Desktop/learn_git/.git/

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git add third.txt

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git commit -m "adding third.txt"
[main 4a19bc7] adding third.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 third.txt

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git log
commit 4a19bc7a9c16e2a524b40f97a5d9f0a48f368979 (HEAD -> main)
Author: IhebZnaidi <ihebzenaidi92@gmail.com>
Date:   Mon May 30 17:13:35 2022 +0100

    adding third.txt

commit 0e1a9e3eefe0ad32eb70f6070e3bedd490b24c62
Author: IhebZnaidi <ihebzenaidi92@gmail.com>
Date:   Mon May 30 16:46:59 2022 +0100

    removing third.txt

commit 28191ee4ff141ae02c6777ae92ba9ef4a3eedfc3
Author: IhebZnaidi <ihebzenaidi92@gmail.com>
Date:   Mon May 30 16:42:31 2022 +0100

    adding third.txt

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git add fourth.txt

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git commit -m "adding fourth.txt"
On branch main
nothing to commit, working tree clean

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git rm third.txt
rm 'third.txt'

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git commit -m "removing third.txt"
[main 1eb3b62] removing third.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 third.txt

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git log
commit 1eb3b625ac22be516204936804195f598b9c5bf3 (HEAD -> main)
Author: IhebZnaidi <ihebzenaidi92@gmail.com>
Date:   Mon May 30 17:15:10 2022 +0100

    removing third.txt

commit 4a19bc7a9c16e2a524b40f97a5d9f0a48f368979
Author: IhebZnaidi <ihebzenaidi92@gmail.com>
Date:   Mon May 30 17:13:35 2022 +0100

    adding third.txt

commit 0e1a9e3eefe0ad32eb70f6070e3bedd490b24c62
Author: IhebZnaidi <ihebzenaidi92@gmail.com>
Date:   Mon May 30 16:46:59 2022 +0100

    removing third.txt

commit 28191ee4ff141ae02c6777ae92ba9ef4a3eedfc3
Author: IhebZnaidi <ihebzenaidi92@gmail.com>
Date:   Mon May 30 16:42:31 2022 +0100

    adding third.txt
d

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ d
sqbash: d: command not found

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ sq
bash: sq: command not found

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git config --global core.pager "cat"

hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git config
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry


hp@DESKTOP-SIIBE5R MINGW64 ~/Desktop/learn_git (main)
$ git config --global
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry
