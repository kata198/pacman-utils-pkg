pacman-utils-pkg
================

This is the pacman PKGBUILD setup for the pacman-utils package.

pacman-utils
------------

Located at: https://github.com/kata198/pacman-utils


Installing
==========

Pre-Built:

Pre-built packages are attached to the releases on github


Manual:

Checkout this directory, or download a release snapshot

Run "makepkg" to build the package

Then, use "pacman -U" to install the package


Dependencies
------------

By default, this package will require some dependency packages, available through AUR.

You can comment out python-func\_timeout and python-cmp\_version and change the line at the top:

    _STANDALONE_VIRTUALENV="false"

to
	
	_STANDALONE_VIRTUALENV="true"


which will build the package using a virtualenv, and thus will require no additional dependencies.
