Bash Prompt Git
===============

Customed powerfull bash prompt.

Features:
 * the history number of this command
 * the command number of this command
 * the date  in  "Weekday  Month  Date"  format (e.g., "Tue May 26")
 * the current time in 24-hour HH:MM:SS format
 * the username of the current user
 * the hostname up to the first `.'
 * the current working directory
 * GIT branch display with sync
 * GIT counter of added, modified, deleted, untracked and stashed files
 * GIT signalization about of ahead/behind remote repository
 * GIT counter of commits about ahed/behind remote repository

Example:
```
    {#33--!531} (lun. oct. 19)-(22:19:42)
    dev@debian:/space/www/silex_api [master] A: 4 M: 1 U: 1 S: 2 U:->1 $
```

More screenshots and demonstration on 

https://github.com/silverpark/bash-git-prompt/wiki/Demonstration


INSTALLATION
============

Run back bash* files
```
    mkdir ~/backup-files
    cp -rfp ~/.bash* ~/backup-files/
```

Copy all '.bash' files to your home directory
```
    git clone git@github.com:silverpark/bash_prompt_git.git
    cd bash_prompt_git
    cp -rfp ./.bash* ~/
    cat .install >> ~/.bashrc
```
