Laptop
======

Laptop is a script to set up a Mac OS X laptop for Rails development.

Requirements
------------

1) Install a C compiler.

Use [OS X GCC Installer](https://github.com/kennethreitz/osx-gcc-installer/) for
Snow Leopard (OS X 10.6).

Use [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action)
for Lion (OS X 10.7) or Mountain Lion (OS X 10.8).

2) Set zsh as your login shell.

    chsh -s /bin/zsh

3) Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) for
vagrant

Install
-------

Run the script:

    zsh < <(curl -s https://raw.github.com/thoughtbot/laptop/master/mac)

What it sets up
---------------

* Ack for finding things in files
* Bundler gem for managing Ruby libraries
* Foreman gem for serving apps locally
* Homebrew for managing operating system libraries
* Postgres for storing relational data
* PostGIS for storing geo-spatial data
* Redis for storing key-value data
* Python, Ruby and Node for writing general-purpose code
* Virtualenv and VirtualenvWrapper for managing python virtual
  environments
* RVM for managing versions of the Ruby programming language
* SSH public key for authenticating with Github and Heroku
* Tmux for saving project state and switching between projects
* Vagrant for managing virtual machines

It should take less than 30 minutes to install (depends on your machine).

Credits
-------

![thoughtbot](http://thoughtbot.com/images/tm/logo.png)

Laptop is maintained and funded by [thoughtbot, inc](http://thoughtbot.com/community).
The names and logos for thoughtbot are trademarks of thoughtbot, inc.

Thank you, [contributors](/thoughtbot/laptop/graphs/contributors)!

License
-------

Laptop is © 2011-2012 thoughtbot, inc. It is free software, and may be
redistributed under the terms specified in the LICENSE file.
