Vagrant.configure("2") do |config|
  config.vm.box="ubuntu/trusty32"
  config.vm.host_name="playbook-lab"
  config.vm.provision "shell", inline: "sudo apt-get install yum ansible -y"
end
