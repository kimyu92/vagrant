# vagrant
Location for simple vagrant files

Since the AMD Hackintosh is not cpu compatible with docker for mac.  I installed vagrant and virtualbox.

Vagrant is avaialable here https://www.vagrantup.com/downloads.html

Virtualbox is available here https://www.virtualbox.org/wiki/Downloads

Virtualbox Extensions are further down the same virtualbox downloads page.

After that it was as simple as creating a basic vm with 8GB of ram and running vagrant up.

Please note this Vagrant file will bump the vm memory in use to 8gb from the standard 1gb and it will request a bridged ip to your local network. It then uses the docker convienience script to install docker and add the vagrant user to the docker group.

This file also installs docker-compose and gives the docker-compose binary execution rights.
