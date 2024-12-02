Vagrant.configure("2") do |config|
  config.vm.box = "generic/ubuntu2004"
  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
    end  

  config.vm.define "blogvm" do |blogvm|
    blogvm.vm.network "private_network", ip: "172.17.177.45"
    end

  config.vm.define "databasevm" do |databasevm|
    databasevm.vm.network "private_network", ip: "172.17.177.46"
    end  
end
