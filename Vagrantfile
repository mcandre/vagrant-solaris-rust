Vagrant.configure("2") do |config|
  config.vm.box = "fla_torres/solaris-11_3"

  # Vagrant does not bother resetting SSH keys to the proper state when
  # packaging boxes for reuse. To work around that limitation, we
  # disable SSH key regeneration for this and all downstream boxes.
  config.ssh.insert_key = false

  # config.vm.provision "shell", path: "bootstrap.sh"
end
