Vagrant.configure("2") do |config|
  config.vm.network "forwarded_port", guest: 5000, host: 5000
  config.vm.box = "idearium/ubuntu-16.04"

  config.vm.provision "file", source: "~/.ssh/id_rsa.pub", destination: "~/.ssh/id_rsa.pub"
  config.vm.provision "file", source: "~/.ssh/id_rsa", destination: "~/.ssh/id_rsa"


end
