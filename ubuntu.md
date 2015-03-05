Ubuntu
======

Common files
------------
- Home folder
- Documents,Downloads,Pictures etc.
- Game data
- Emails
- Bookmarks, shortcuts

Packages
--------------------------
- List of installed packages - `dpkg --get-selections | grep -v deinstall`
- Sources file - `etc/apt/sources.list`

Configuration files
-------------------
- .bash_logout - file executed by bash shell on logout
- .bash_profile - initialization of bash shell run only on login.
- .bashrc - initialization command run when bash shell starts up as a non-login shell
- .cshrc - initialization commands that are run automatically when C shell is initiated
- .emacs - configuration file for emacs editor
- .gitconfig - configuration file for github
- .lessrc - typically contains key bindings for cursor movement with the less command
- .login - initialization file when user logs in
- .logout - commands run when user logs out
- .vimrc - configuration file for vim editor

SSH Keys
--------
- `~/.ssh` folder

Fonts
-----
`/usr/share/fonts`
`/usr/local/share/fonts`
`/home/<username>/.fonts` #where `<username>` is your user name

Drivers
-------
`/lib/modules/`

Offline websites
--------------
- localhost (www)
- phpMyAdmin databases

Android/Java Projects
---------------------
- workspace folder
