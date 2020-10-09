# generic-box

User customizable developer box for general-purpose.


## Getting started

```
$ git clone https://github.com/extra2000/generic-box.git
$ cd generic-box
```


## Preparing environment

Rename the following files:
* `salt/etc/minion.example` to `salt/etc/minion`
* `vagrant/Vagrantfile.generic-box.example` to `vagrant/Vagrantfile.generic-box`

You may need to modify configs in `salt/etc/minion` and `vagrant/Vagrantfile.generic-box`.

Then, create the Vagrant box:
```
$ vagrant up --provider=libvirt
```
