# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ARTACK/debian-jessie"
  config.vm.network "forwarded_port", guest: 80, host: 8080
  config.vm.synced_folder "~/dev", "/vagrant_data"
  config.vm.provider "virtualbox" do |vb|
     vb.memory = "1024"
  end
end
