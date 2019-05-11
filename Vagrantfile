# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  ### balanceador
   config.vm.define "balanceador" do |balanceador|
       balanceador.vm.box = "hashicorp/precise64"
       balanceador.vm.hostname = "balanceador"
       balanceador.vm.network "private_network", ip:"192.168.50.4"
       balanceador.vm.provider "virtualbox" do |v|
         v.memory = 512
         v.cpus = 2
       end
    end
###web1
   config.vm.define "web1" do |web1|
       web1.vm.box = "hashicorp/precise64"
       web1.vm.hostname = "web1"
       web1.vm.network "private_network", ip:"192.168.50.5"
       web1.vm.provider "virtualbox" do |v|
         v.memory = 512
         v.cpus = 2
       end
    end
###web2
   config.vm.define "web2" do |web2|
       web2.vm.box = "hashicorp/precise64"
       web2.vm.hostname = "web2"
       web2.vm.network "private_network", ip:"192.168.50.6"
       web2.vm.provider "virtualbox" do |v|
         v.memory = 512
         v.cpus = 2
       end
    end
end
