# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure(2) do |config|

  config.ssh.username = "vagrant"
  config.ssh.password = "vagrant"

  config.vm.box = "bxav/yunohost"

  config.vm.network "private_network", ip: "192.168.33.10", auto_config: false

  config.vm.synced_folder ".", "/app"

  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
  end
end
