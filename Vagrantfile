# -*- mode: ruby -*-
# vi: set ft=ruby :


box = "bento/centos-7.3"

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
    config.vm.box = "#{box}"

    # Box Specifications
    config.vm.provider :virtualbox do |vb|
      vb.memory = 4096
      vb.cpus = 2
    end

    config.vm.provider :vmware_fusion do |vf|
      vf.vmx["memsize"] = "4096"
      vf.vmx["numvcpus"] = "2"
    end
end