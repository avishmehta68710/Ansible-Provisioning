Vagrant.configure("2") do |config|

  config.vm.define "ubuntu-bionic64-Vagrant" do |ubuntu|
    ubuntu.vm.box = "ubuntu/bionic64"
    ubuntu.vm.network :private_network, ip: "192.168.56.111"
    ubuntu.vm.provider :virtualbox do |y|
      y.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      y.customize ["modifyvm", :id, "--memory", 1500]
      y.customize ["modifyvm", :id, "--cpus", 3]
      y.customize ["modifyvm", :id, "--name", "Ubuntu-Vagrant"]
      y.customize ["modifyvm", :id, "--hwvirtex", "off"]
      y.name = 'Ubuntu-bionic64-Vagrant'
      y.gui = false
    end
  end

  config.vm.define "Centos-7-Vagrant" do |centos7|
    centos7.vm.box = "centos/7"
    centos7.vm.network :private_network, ip: "192.168.56.121"
    centos7.vm.provider :virtualbox do |x|
      x.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      x.customize ["modifyvm", :id, "--memory", 1500]
      x.customize ["modifyvm", :id, "--cpus", 3]
      x.customize ["modifyvm", :id, "--name", "Centos-7-Vagrant"]
      x.customize ["modifyvm", :id, "--hwvirtex", "off"]
      x.name = 'Centos-7-Vagrant'
      x.gui = false
    end
  end

  config.vm.define "Kali-Vagrant" do |kali|
    kali.vm.box = "kalilinux/rolling"
    kali.vm.network :private_network, ip: "192.168.56.131"
    kali.vm.provider :virtualbox do |z|
      z.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      z.customize ["modifyvm", :id, "--memory", 1500]
      z.customize ["modifyvm", :id, "--cpus", 3]
      z.customize ["modifyvm", :id, "--name", "Kali-Vagrant"]
      z.customize ["modifyvm", :id, "--hwvirtex", "off"]
      z.name = 'Kali-Vagrant'
      z.gui = false
    end
  end

  config.vm.define "Windows-Vagrant" do |windows|
    windows.vm.box = "gusztavvargadr/windows-10"
    windows.vm.network :private_network, ip: "192.168.56.141"
    windows.vm.provider :virtualbox do |q|
      q.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      q.customize ["modifyvm", :id, "--memory", 1500]
      q.customize ["modifyvm", :id, "--cpus", 3]
      q.customize ["modifyvm", :id, "--name", "Windows-Vagrant"]
      q.customize ["modifyvm", :id, "--hwvirtex", "off"]
      q.name = 'Windows-Vagrant'
      q.gui = false
    end
  end

  config.vm.define "ArchLinux-Vagrant" do |archlinux|
    archlinux.vm.box = "archlinux/archlinux"
    archlinux.vm.network :private_network, ip: "192.168.56.151"
    archlinux.vm.provider :virtualbox do |j|
      j.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      j.customize ["modifyvm", :id, "--memory", 1500]
      j.customize ["modifyvm", :id, "--cpus", 3]
      j.customize ["modifyvm", :id, "--name", "ArchLinux-Vagrant"]
      j.customize ["modifyvm", :id, "--hwvirtex", "off"]
      j.name = 'ArchLinu-Vagrant'
      j.gui = false
    end
  end

end
