Vagrant.configure("2") do |config|
  # Nodo 1: soufe1
  config.vm.define "soufe1" do |node|
    node.vm.box = "generic/oracle8"
    node.vbguest.auto_update = false
    node.vm.network "private_network", ip: "192.168.50.111"
    node.vm.provision "ansible" do |ansible|
      ansible.playbook = "./deploy.yml"
      ansible.become = true
    end
    node.vm.provider "virtualbox" do |v|
      v.memory = 2048
      v.cpus = 1
    end
  end

  # Nodo 2: soube2
  config.vm.define "soube2" do |node|
    node.vm.box = "generic/oracle8"
    node.vbguest.auto_update = false
    node.vm.network "private_network", ip: "192.168.50.112"
    node.vm.provision "ansible" do |ansible|
      ansible.playbook = "./deploy.yml"
      ansible.become = true
    end
    node.vm.provider "virtualbox" do |v|
      v.memory = 2048
      v.cpus = 1
    end
  end
end
