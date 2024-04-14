Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.base_address = "10.10.10.10"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
    vb.cpus = 1
  end

  config.vm.provision "shell", path: "script_docker.sh"
end
