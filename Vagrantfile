Vagrant.configure("2") do |config|
  config.vm.define :Ubuntu16 do |master_config|
    master_config.vm.box = "ubuntu/xenial64"
    master_config.vm.host_name = 'Ubuntu16'
    master_config.vm.network "private_network", ip: "192.168.50.50"
  end
  config.vm.define :CentOS7 do |master_config|
    master_config.vm.box = "centos/7"
    master_config.vm.host_name = 'CentOS7'
    master_config.vm.network "private_network", ip: "192.168.50.51"
  end
 end

