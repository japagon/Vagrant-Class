# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "debian/bullseye64"
  config.ssh.insert_key = false

  config.vm.define "web" do |web|
      web.vm.hostname = web 
      web.vm.network :private_network, ip "127.0.0.1"
  end
end
