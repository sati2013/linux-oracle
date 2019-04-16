# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.require_version "> 1.7.0"
Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.provision "ansible" do |ansible|
    ansible.verbose = "v"
    ansible.playbook = "oracle-db.yml"
  end
  #config.vm.synced_folder "/Users/000tri/codingStartHere/Lab/tools","/tools"
  #  #config.vm.network "forwarded_port", guest: 22, host: 22223, host_ip: "127.0.0.1"
end
