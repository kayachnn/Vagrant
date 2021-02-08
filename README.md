Vagrant

#Create a box
Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/bionic64"
end



#Boot an environment
Vagrant up



#SSH into machine
vagrant ssh



#Destroy the machine
vagrant destroy


#Remove the box
vagrant box list

vagrant box remove <box-name>

