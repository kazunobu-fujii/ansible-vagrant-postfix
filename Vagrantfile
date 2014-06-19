VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.define "postfix.vagrant.local" do |node|
    node.vm.box = "hashicorp/precise32"
    node.vm.network "private_network", ip: "192.168.33.30"
  end
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end
end
