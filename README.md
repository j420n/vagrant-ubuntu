##Vagrant Development Environment
>This Vagrant setup is used to test the [silex-puppet-control] repo on a Ubuntu 14.04 virtual machine.

To test:

    git clone https://github.com/j420n/vagrant-ubuntu.git
    cd vagrant-ubuntu
    vagrant up
    vagrant ssh

Yes, it is that easy.

The machine is provisioned with the script [here]

[here]: https://raw.githubusercontent.com/j420n/silex-puppet-control/vagrant/provision-ubuntu.sh

[silex-puppet-control]: https://github.com/j420n/silex-puppet-control.git
