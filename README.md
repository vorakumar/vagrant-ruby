vagrant-ruby
============

Create vagrant box with rvm and ruby pre-installed

Steps to install
----------------

1. Install librarian [https://github.com/applicationsonline/librarian]

    bundle install

2. Install the cookbooks required to setup rvm & apt. It depends on apt cookbook to add ubuntu-on-rails repo 

    librarian-chef install

3. Initialize vagrant
    
    vagrant up
