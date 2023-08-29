
## 1 - Installation

  Install Virtualbox and Vagrant on local machine
  https://www.howtoforge.com/how-to-install-vagrant-on-ubuntu-20-04/

## 2 - Build the Virtual Machine

  1. Download this project and put it wherever you want.
  2. Open Terminal, cd to this directory.
  4. Type in `vagrant up`, and let Vagrant do its magic.

Note: *If there are any errors during the course of running `vagrant up`, and it drops you back to your command prompt, just run `vagrant provision` to continue building the VM from where you left off. If there are still errors after doing this a few times, post an issue to this project's issue queue on GitHub with the error.*

## Notes

  - To shut down the virtual machine, enter `vagrant halt` in the Terminal in the same folder that has the `Vagrantfile`. To destroy it completely (if you want to save a little disk space, or want to rebuild it from scratch with `vagrant up` again), type in `vagrant destroy`.
