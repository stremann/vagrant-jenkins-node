Jenkins CI Server: JavaScript Tech Mentoring
=========
Travis is cool. Coveralls is hip. But Jenkins has had this stuff for a while, and more.

* Vagrant: https://www.vagrantup.com/
* VirtualBox: http://www.oracle.com/technetwork/server-storage/virtualbox/downloads/index.html
* PuTTY: http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html
* Localtunnel: https://github.com/localtunnel/localtunnel


Starting
---------
[Once you have clone the repository](https://github.com/stremann/vagrant-jenkins-node), just run:

    vagrant up

Connecting
-------------
Make SSH connection as vagrant@vagrant user on:

    127.0.0.1:2222

In case you want to share your Jenkins instance, you could use localtunnel util

Vagrant commands
-------------
* Shell connect to VM `vagrant ssh` (for convenience ‘vagrant’ is a no-passwd sudo user)
* Pause VM `vagrant suspend`
* Start suspendend VM `vagrant resume`
* Halt VM `vagrant halt`
* Start halted VM `vagrant up`
* Completely remove the VM `vagrant destroy`
* Re-provision VM `vagrant provision` (useful when tweaking provisioning scripts)
