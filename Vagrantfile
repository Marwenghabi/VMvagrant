Vagrant.configure("2") do |config|

  config.vm.box = "rockylinux/9"

  config.disksize.size = '50GB'

  config.vm.hostname = "rocky"

  config.vm.define "foohost"

  config.vm.network "public_network", ip: "192.168.1.131"

  config.vm.provider :virtualbox do |vb|

      vb.name = "RockyLinux"

      vb.memory = "4096"

  end

end