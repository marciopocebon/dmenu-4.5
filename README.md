dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X.

This is my personal fork with several patches:

- bash_aliases

    Run dmenu with custom aliases defined in $HOME/.bash_aliases

- xkbswitch

    Switch to Lating keyboard layout before starting input


These patches are implemented in the dmenu_run file and do not
affect the source code of dmenu.

Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.
