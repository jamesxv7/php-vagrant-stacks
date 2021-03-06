# PHP Vagrant Stacks
Manually curated selection of various stacks configurations for rapid creation of development environments in PHP.

### [panique/vagrant-lamp-bootstrap](https://github.com/panique/vagrant-lamp-bootstrap)
Excelent PHP stack. Just the basic components. 

### [scotch-io/scotch-box](https://github.com/scotch-io/scotch-box)
Very similar to [panique/vagrant-lamp-bootstrap](https://github.com/panique/vagrant-lamp-bootstrap) with a few extras.

### [chad-thompson/vagrantpress](https://github.com/chad-thompson/vagrantpress)
Ideal box for Wordpress Theme Development.

### [Laravel Homestead](http://laravel.com/docs/4.2/homestead)
De facto box of the [Laravel Framework](http://laravel.com/).

### [kleiram/vagrant-symfony](https://github.com/kleiram/vagrant-symfony)
Vagrant configuration for Symfony development. Provision is through Ansible so Windows users will not be able to use it unless by changing the provisioning provider. 

### [rlerdorf/php7dev](https://github.com/rlerdorf/php7dev)
Vagrant configuration preconfigured for testing PHP apps and developing extensions across many versions of PHP.


## Basic stuff to remeber before use one of this configuration. 

1. Check that your host machine has Virtualization Technology enable on the Bios Utilities. Most applicable for Windows users. 
2. Virtual Box and Vagrant should be already installed in your host machine.
3. Read at least the [Getting Started](https://docs.vagrantup.com/v2/getting-started/) section of the Vagrant documentation.


## Extra Tools

### Vagrant Manager for [OS X](http://vagrantmanager.com/) and [Windows](http://vagrantmanager.com/windows/)
A tool that I recently added to the development workflow. Right now Open Source for OS X and Windows.

### Want a custom solution?
Try the one of following services:  [PuPHPet](https://puphpet.com/) or
[Rove.io](http://rove.io/). They basically create everything that is needed to boot the virtual machine. Also they provide the configurations files to start creating the development environment according to your needs.
