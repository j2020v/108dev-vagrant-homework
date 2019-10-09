# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/xenial64"
  config.vm.network "private_network", ip: "192.168.10.100" #method call and string arguments , ip is a key -- dictionary
  config.hostsupdater.aliases = ["jillian.local"]

  #synced app folder
  #config.vm.synced_folder "app", "/app"

  #provision bash script
  #config.vm.provision "shell", path: "environment/provision.sh"


end
