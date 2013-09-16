vagrant-starter
===============

Vagrant + Puppet Starter project

Run `vagrant up` at the root of this repository to provision the default vm
with puppet.

Bootstrap.sh installs puppet on Red hat and Debian based systems.
Default box is 'Ubuntu Server 12.04.2 x64'.
All puppet modules go in 'puppet/modules', any server classification goes in
'puppet/manifests'.
