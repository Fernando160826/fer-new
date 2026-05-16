$ git init
Reinitialized existing Git repository in C:/Users/ff897/.git/

ff897@DESKTOP-FLHTU4G MINGW64 ~ (main)
$ touch farmacia.txt

ff897@DESKTOP-FLHTU4G MINGW64 ~ (main)
$ git app
git: 'app' is not a git command. See 'git --help'.

The most similar command is
        apply

ff897@DESKTOP-FLHTU4G MINGW64 ~ (main)
$ git add farmacia.txt
fatal: Unable to create 'C:/Users/ff897/.git/index.lock': File exists.

Another git process seems to be running in this repository, or the lock file may be stale

ff897@DESKTOP-FLHTU4G MINGW64 ~ (main)
$ git commit -m "fer.new"
fatal: Unable to create 'C:/Users/ff897/.git/index.lock': File exists.

Another git process seems to be running in this repository, or the lock file may be stale

ff897@DESKTOP-FLHTU4G MINGW64 ~ (main)
$ git remote add origin https://github.com/Fernando160826/fer-new.
error: remote origin already exists.

ff897@DESKTOP-FLHTU4G MINGW64 ~ (main)
$ git push -u origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

ff897@DESKTOP-FLHTU4G MINGW64 ~ (main)
$
