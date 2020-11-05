# generic-box

| License | Versioning | Build |
| ------- | ---------- | ----- |
| [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) | [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release) | [![Build Status](https://travis-ci.com/extra2000/generic-box.svg?branch=master)](https://travis-ci.com/extra2000/generic-box) [![Build status](https://ci.appveyor.com/api/projects/status/vjocnhar8uvvykbe/branch/master?svg=true)](https://ci.appveyor.com/project/nikAizuddin/generic-box/branch/master) |

User customizable developer box for general-purpose.


## Getting started

```
$ git clone https://github.com/extra2000/generic-box.git
$ cd generic-box
```


## Preparing environment

Rename the following files:
```
$ cp -v salt/etc/minion.example salt/etc/minion
$ cp -v vagrant/Vagrantfile.generic-box.centos-7.x86_64.example vagrant/Vagrantfile.generic-box
```

You may need to modify configs in `salt/etc/minion` and `vagrant/Vagrantfile.generic-box`.

Then, create the Vagrant box:
```
$ vagrant up --provider=libvirt
```
