Vagrant.configure("2") do |config|
  
  config.vm.box = "bento/ubuntu-16.10"
  config.vm.network "forwarded_port", guest: 3000, host: 8000
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"

  end

end