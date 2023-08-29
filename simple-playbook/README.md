
## 1 - Installation

  Install Virtualbox and Vagrant on local machine
  <br>https://www.howtoforge.com/how-to-install-vagrant-on-ubuntu-20-04/

## 2 - Build the Virtual Machine

  Clone Image
  <br>Go into the folder
  <br>vagrant init hashicorp/precise32
  <br>vagrant up  //edit building may take some time

## Notes

  - To shut down the virtual machine, enter `vagrant halt` in the Terminal in the same folder that has the `Vagrantfile`. To destroy it completely (if you want to save a little disk space, or want to rebuild it from scratch with `vagrant up` again), type in `vagrant destroy`.
