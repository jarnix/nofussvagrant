# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.box = "nofussvm"
  config.vm.box_url = "https://github.com/jarnix/nofussvagrant/releases/download/1.0/package.box"
  
  # adds a forwarded port
  config.vm.network "forwarded_port", guest: 80, host: 8888

  # config.vm.box_check_update = false
end
