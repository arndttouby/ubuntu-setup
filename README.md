Laptop
======

Laptop is a script to set up a Linux laptop for Rails development.

Requirements
------------

### Linux

We support:

* [12.04 LTS: Precise Pangolin](https://wiki.ubuntu.com/PrecisePangolin/ReleaseNotes),
* [13.04: Raring Ringtail](https://wiki.ubuntu.com/RaringRingtail/ReleaseNotes),
* [12.10: Quantal Quetzal](https://wiki.ubuntu.com/QuantalQuetzal/ReleaseNotes), and
* Debian testing (currently [wheezy](http://www.debian.org/releases/testing/)).

Install
-------

### Linux

Read, then run the script:

   wget -O- https://raw.github.com/arndttouby/ubuntu-setup/master/linux | bash

What it sets up
---------------

* Bundler gem for managing Ruby libraries
* Exuberant Ctags for indexing files for vim tab completion
* Foreman gem for serving Rails apps locally
* Heroku Config plugin for local `ENV` variables
* Heroku Toolbelt for interacting with the Heroku API
* Hub gem for interacting with the GitHub API
* ImageMagick for cropping and resizing images
* Postgres for storing relational data
* Postgres gem for talking to Postgres from Ruby
* Qt for headless JavaScript testing via Capybara Webkit
* Rails gem for writing web applications
* RVM for managing versions of the Ruby programming language
* Redis for storing key-value data
* The Silver Searcher for finding things in files
* Tmux for saving project state and switching between projects
* Watch for periodically executing a program and displaying the output

It should take less than 15 minutes to install (depends on your machine).
