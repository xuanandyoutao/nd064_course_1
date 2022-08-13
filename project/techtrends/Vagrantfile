ENV["TERM"]="linux"

Vagrant.configure("2") do |config|

  config.vm.box = "opensuse/Leap-15.2.x86_64"
  config.vm.box_version = "15.2.31.632"
  config.vm.network "private_network", ip: "192.168.56.4"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
    vb.cpus = 2
    vb.customize ["modifyvm", :id, "--ioapic", "on"]
  end
end
