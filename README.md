# Config scripts for Ubuntu

Common scripts and configuration files used in more than one Ubuntu configuration. This does not automatically install anything; it is only a library containing assets that other provisioning scripts may use.

## Contents

* apply_updates - bring the installed system up to date.
* disable_crash_reports - set enabled=0 in /etc/default/apport to suppress bogus crash report notifications.
* dropbox.py - Dropbox client script to be copied to the installed system.
* install_build_support - packages needed to compile and make.
* install_dropbox - install Dropbox daemon.
* install_epiphany_browser - installs Epiphany web browser and its dependencies.
* install_midori_browser - installs Midori web browser and its dependencies.
* install_openssh - installs OpenSSH client and server packages.
* install_sublime_text_3 - installs and configures Sublime Text 3.
* install_vmware - installs VMware Player.
* install_yed - installs yEd diagramming tool.
* install_xwindows_support - installs X Windows packages.
* ubuntu_update - applies all available updates to the instance.
* xubuntu_cleanup - removes some of the packages that are included in the Xubuntu Desktop distro.
* LICENSE
* README.md
* sublime-text-3/ - config files that are copied or merged after the basic install of Sublime Text 3
