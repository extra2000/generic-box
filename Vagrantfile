# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vagrant.plugins = ["vagrant-reload", "vagrant-scp"]
end

generic_box_vagrantfile = './vagrant/Vagrantfile.generic-box'
load generic_box_vagrantfile if File.exists?(generic_box_vagrantfile)
