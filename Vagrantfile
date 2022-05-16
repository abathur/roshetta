Vagrant.configure("2") do |config|
  config.vm.box = "fedora/31-cloud-base"
  config.vm.provider :libvirt do |libvirt|
    libvirt.connect_via_ssh = true
    libvirt.driver = "qemu"
  end
end
