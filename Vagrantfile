Vagrant.configure(2) do |config|
  config.vm.box = "centos/7"
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.hostname = "client.vagrant.local"
  config.vm.provider "virtualbox" do |v|
    v.memory = 512
    v.cpus = 1
    v.name = "webserver"
  end
end
