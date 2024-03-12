# -*- mode: ruby -*-
# vi: set ft=ruby :
ENV['VAGRANT_SERVER_URL']="https://vagrant.elab.pro"

Vagrant.configure(«2») do |config|
 config.vm.box = «ubuntu/xenial64»

 config.vm.provision «shell», inline: <<-SHELL
  apt-get update
  apt-get -y upgrade
  apt-get install -y postgresql-8.4

 SHELL
end
