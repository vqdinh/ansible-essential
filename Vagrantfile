VAGRANTFILE_API_VERSION = "2"
  
Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
#  config.vm.box = "ubuntu/xenial64"
  config.vm.box = "ubuntu/xenial64"
  config.vm.provider "virtualbox"

  config.vm.define "control" do |control|
    control.vm.network :private_network, ip: "192.168.56.10"
  end

  config.vm.define "host1" do |host1|
    host1.vm.network :private_network, ip: "192.168.56.20"
  end

  config.vm.define "host2" do |host2|
    host2.vm.network :private_network, ip: "192.168.56.21"
  end

  config.vm.define "host3" do |host3|
    host3.vm.network :private_network, ip: "192.168.56.22"
  end

end