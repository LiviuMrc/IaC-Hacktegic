Vagrant.configure("2") do |config|
  config.vm.box = "generic/fedora33"
  
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end
end
