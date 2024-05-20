
Vagrant.configure("2") do |config|
  
  config.vm.box = "ubuntu/xenial64"

  # Configuração de recursos
  config.vm.provider "virtualbox" do |vb|
    vb.memory = 3048 # 3GB de memória RAM
    vb.cpus = 1      # 1 CPUs
  end
  
  # Configuração de rede
  config.vm.network "public_network", bridge: "enp6s0"
end
