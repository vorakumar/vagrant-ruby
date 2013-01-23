# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant::Config.run do |config|
  # All Vagrant configuration is done here. The most common configuration
  # options are documented and commented below. For a complete reference,
  # please see the online documentation at vagrantup.com.

  # Every Vagrant virtual environment requires a box to build off of.
   config.vm.box = "sandbox"

      #config.vm.box_url = "http://files.vagrantup.com/precise64.box"
      config.vm.provision :chef_solo do |chef|
      chef.cookbooks_path = ["cookbooks", "vendor-cookbooks"] 
      chef.roles_path = "roles"
      chef.add_role "default"
  end

end
