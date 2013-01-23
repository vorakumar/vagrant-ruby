vagrant-ruby
============

Create vagrant box with rvm and ruby pre-installed

Steps to install
----------------

1. Install librarian

    bundle install

2. Install the cookbooks required to setup rvm & apt. It depends on apt cookbook to add ubuntu-on-rails repo 

    librarian-chef install

3. Initialize vagrant
    
    vagrant up

4. Start using your vagrant box!!!!
	
    vagrant ssh



The setup leverages following chef cookbooks and ruby  gems:

* gem: librarian [https://github.com/applicationsonline/librarian]

* cookbook: rvm [git://github.com/fnichol/chef-rvm.git] -  v0.9.0

* cookbook: apt [git://github.com/opscode-cookbooks/apt.git] - v1.7.0

