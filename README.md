PAC-Man ROM
===========

Submitting Patches
------------------
We're open source, and patches are always welcome!
You can send patches by using these commands:

    cd <workspace>
    repo start <branch> <project>
    cd <project>
    git add <file you edited>
    git commit
    cd <workspace>
    repo upload <project>
    
    cd <workspace>

Commit your patches in a single commit. Squash multiple commit using this command: git rebase -i HEAD~<# of commits>

If you are going to make extra additions, just repeat steps (Don't repo start again), but instead of git commit -a
use git commit --amend. Gerrit will recognize it as a new patchset.

To view the status of your and others patches, visit [PAC-Man ROM Code Review](http://review.pac-man-rom.de:8080/)


Getting Started
---------------

To get started with PAC-Man, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the PAC-Man trees, use a command like this:

    repo init -u git://github.com/PAC-man/android.git -b <branch>

Then to sync up:

    repo sync
    
Then to build:

    ./build-pac.sh <device_name>



For information on how to build, check [Here](http://forum.xda-developers.com/showthread.php?t=2060017)

Our Official Forum : [Forum](http://pac-man-rom.de/forum/)

Our Official IRC : [#pac-rom](http://webchat.freenode.net/?channels=pac-rom)
