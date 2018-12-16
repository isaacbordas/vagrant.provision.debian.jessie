#vagrant.provision.debian.jessie

Provisioning vagrant box debian/jessie64

This Vagrant script creates a Debian's Jessie 64bit machine and provide it via owns machine SHELL with a LAMP environment with the next actions:

    Install lastest Apache
    Adds repository for the PHP 7.2
    Installs PHP 7.2 with extensions
    Installs latest MySQL indicating the root password on the process
    Installs composer and makes it global
    Installs Git
    Installs unzip

Change the default password for the MySQL root user located in the Vagrantfile The local IP for this machine is 192.168.33.177. Change it for your convenience. The synced_folder is web (relative on the Vagrantfile location) -> /var/www (default DocumentRoot folder for apache)
