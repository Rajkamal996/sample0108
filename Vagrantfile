	Vagrant.configure("2") do |config| 
    config.vm.define "minikube" do |minikube|
    minikube.vm.box = "ubuntu/bionic64"
	minikube.vm.hostname = "minikube"
    minikube.vm.network "private_network", ip: "192.168.33.102"
	minikube.vm.provider "virtualbox" do |vb|
	vb.memory = "4096"
end
end
end