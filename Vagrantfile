# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant::Config.run do |config|
  config.vm.box = "lucid32"
  config.vm.forward_port 80, 8080
  config.vm.customize ["modifyvm", :id,  "--natdnshostresolver1", "on", "--memory", 512]
end
