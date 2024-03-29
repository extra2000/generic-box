# Changelog

## [1.10.0](https://github.com/extra2000/generic-box/compare/v1.9.0...v1.10.0) (2022-07-07)


### Features

* **vagrantfiles:** update SaltStack from `3004` to `3004.2` ([64e8690](https://github.com/extra2000/generic-box/commit/64e8690e99895e3bef7a7174de0ce44f352eb5cd))


### Fixes

* **opensuse/aarch64/qemu:** add UEFI image provided by `edk2-aarch64` package ([5459417](https://github.com/extra2000/generic-box/commit/54594175216bbeabb30c518a3a9ec19d65e12961))
* **tumbleweed/aarch64/qemu:** remove deprecated `sysvinit-tools` and `insserv-compat` packages ([c69cafc](https://github.com/extra2000/generic-box/commit/c69cafcdbe274eaf2bb47ffa32540d07a4081142))


### Continuous Integrations

* **AppVeyor:** change Vagrant installation method ([5c2ffee](https://github.com/extra2000/generic-box/commit/5c2ffee6af5149a068e7d5454856459e04706f29))
* **AppVeyor:** remove unused `git submodule` command ([12715ae](https://github.com/extra2000/generic-box/commit/12715ae1c5a8ee5f885fa4c03b47ab384456e391))

## [1.9.0](https://github.com/extra2000/generic-box/compare/v1.8.0...v1.9.0) (2021-12-05)


### Features

* **saltstack:** upgrade from `v3003` to `v3004` ([c479859](https://github.com/extra2000/generic-box/commit/c4798597f3ac8ab67113b0dcd258d4648aff07ac))
* **vagrant:** add AlmaLinux 8.5 box ([59c264a](https://github.com/extra2000/generic-box/commit/59c264aa25006e26e8732997a91c4cda4577f674))


### Documentations

* **README:** change default box from `Fedora 34` to `AlmaLinux 8.5` ([353c232](https://github.com/extra2000/generic-box/commit/353c232c2360b828247bbfecb850301d47fb58c0))


### Styles

* **README:** remove `$` sign to simplify copy-paste commands ([2b5d77c](https://github.com/extra2000/generic-box/commit/2b5d77c6c124a70aa6c9c0308bd747b110b317ab))


### Continuous Integrations

* **AppVeyor:** change `Fedora 33` to `AlmaLinux 8.5` ([cf97f41](https://github.com/extra2000/generic-box/commit/cf97f4153af26c2c501837d8086afb7fdfa9b8b0))

## [1.8.0](https://github.com/extra2000/generic-box/compare/v1.7.0...v1.8.0) (2021-04-28)


### Features

* **vagrant:** Add Fedora 34 `x86_64` Vagrant file ([5126881](https://github.com/extra2000/generic-box/commit/512688159114e1f94607a62f950e35c9fc64916a))


### Documentations

* **README:** Set Fedora 34 as default Vagrant instruction ([f662640](https://github.com/extra2000/generic-box/commit/f66264097353bf3c9657ec49a653ff27144bfde5))

## [1.7.0](https://github.com/extra2000/generic-box/compare/v1.6.0...v1.7.0) (2021-04-13)


### Features

* **vagrant:** Upgrade SaltStack from version `3002.6` to version `3003` ([444ac25](https://github.com/extra2000/generic-box/commit/444ac25adec57a0f8f7af9b5a676bd93ba37d126))

## [1.6.0](https://github.com/extra2000/generic-box/compare/v1.5.0...v1.6.0) (2021-03-29)


### Features

* **vagrant:** Upgrade SaltStack from `3002.2` to `3002.6` ([efd349f](https://github.com/extra2000/generic-box/commit/efd349f0de897587be54cb7a41388cbda69e0bad))


### Fixes

* **/etc/minion:** Using new style for `module.run` ([ad39cd5](https://github.com/extra2000/generic-box/commit/ad39cd544a009c621f6e51730d5941afc94de279))


### Continuous Integrations

* **AppVeyor:** Upgrade `nvm` from `v0.33.0` to `v0.37.2` ([7bb793b](https://github.com/extra2000/generic-box/commit/7bb793ba4b0fd973f3fbe37ceae8f0e57e0394ef))
* **AppVeyor:** Upgrade Vagrant from version `2.2.9` to `2.2.14` ([87c6dc9](https://github.com/extra2000/generic-box/commit/87c6dc98330665749f99266b8b2904cce23d80c0))

## [1.5.0](https://github.com/extra2000/generic-box/compare/v1.4.2...v1.5.0) (2021-02-11)


### Features

* **vagrant:** Add `storage_pool_name` option ([9e13a58](https://github.com/extra2000/generic-box/commit/9e13a584e4698581099e246d8f5e0cd7bddee5f2))


### Code Refactoring

* **gitignore:** Remove duplicated rules ([fb0ae2a](https://github.com/extra2000/generic-box/commit/fb0ae2ab41ecf5d51c9866f7042ce39e798e1757))


### Documentations

* **README:** Set Fedora 33 `x86_64` as default ([e9a2dcb](https://github.com/extra2000/generic-box/commit/e9a2dcb65fd3a36e0ee55dd08d592046fddb85d8))


### Continuous Integrations

* **AppVeyor:** Make `gitsubmodule` update with `--init` and `--recursive` ([63a4c05](https://github.com/extra2000/generic-box/commit/63a4c05d561d9a73ba487c8b10164acf69669439))

### [1.4.2](https://github.com/extra2000/generic-box/compare/v1.4.1...v1.4.2) (2021-01-21)


### Fixes

* **vagrant:** Fix Salt Minion installation isses on openSUSE Leap and Tumbleweed ([aa545ae](https://github.com/extra2000/generic-box/commit/aa545ae0b7cb7d28a0331c719c3f40204a5f0464))

### [1.4.1](https://github.com/extra2000/generic-box/compare/v1.4.0...v1.4.1) (2021-01-20)


### Continuous Integrations

* **AppVeyor:** Upgrade Ubuntu from `18.04` to `20.04` ([a3755c6](https://github.com/extra2000/generic-box/commit/a3755c6b188bc7de83dc12f726f59589918bcf3f))

## [1.4.0](https://github.com/extra2000/generic-box/compare/v1.3.0...v1.4.0) (2021-01-07)


### Features

* **vagrant:** Add nested virtualization option for VirtualBox provider ([e683a94](https://github.com/extra2000/generic-box/commit/e683a94ea68f5943aa97fbb8b1c7a8e58d53e810))


### Code Refactoring

* **vagrant:** Remove `sudo` and replace with `privileged: true` ([3db7bd0](https://github.com/extra2000/generic-box/commit/3db7bd0c78e71a073d8f6f8e693f1b287ffe3490))


### Fixes

* **vagrant:** Fix missing `python3-pip` and `python3-setuptools` installation for OpenSUSE Leap 15.2 Virtualbox provider ([5dd8bfa](https://github.com/extra2000/generic-box/commit/5dd8bfa41bce8eb89152bae16991399ec23b832e))
* **vagrant:** Fix missing Salt dependencies for OpenSUSE `aarch64` boxes ([b0107df](https://github.com/extra2000/generic-box/commit/b0107dfb299b07bd575b9a37ffaa95332df46f91))

## [1.3.0](https://github.com/extra2000/generic-box/compare/v1.2.0...v1.3.0) (2020-12-27)


### Features

* **vagrant:** Add CentOS 8 `x86_64` box ([2b39249](https://github.com/extra2000/generic-box/commit/2b39249db83a63ca8f35f07209e22360c952371b))
* **vagrant:** Add CentOS Stream `x86_64` box ([aa897c5](https://github.com/extra2000/generic-box/commit/aa897c5edd9f20268a3059994dd07ad7ff80da0a))
* **vagrant:** Add Fedora 33 `x86_64` box ([2e82d21](https://github.com/extra2000/generic-box/commit/2e82d210a65dfb9cbbe58bcfef86e0a60cf05cee))
* **vagrant:** Add Ubuntu 18.04 `x86_64` box ([e18e6b5](https://github.com/extra2000/generic-box/commit/e18e6b5308385d052ade52a4d8b101a24aae0756))
* **vagrant:** Enable VNC by default, for Libvirt provider ([215b15c](https://github.com/extra2000/generic-box/commit/215b15c7a9a76842816b6b5f538a77dd02993058))


### Fixes

* **vagrant:** Change Salt install type from `stable` to `git` with Salt version `3002.2` to ensure all Vagrant boxes are using the same Salt version ([02f51c5](https://github.com/extra2000/generic-box/commit/02f51c5ab05b4cc0f0d55f80be45d8fd7b3988dd))
* **vagrant:** Explicitly force using Python3 via `-x python3` argument ([6124968](https://github.com/extra2000/generic-box/commit/6124968c22f0604df563ce9691a336c7f4a49520))


### Continuous Integrations

* **AppVeyor:** Change CentOS 7 to Fedora 33 ([af7b53e](https://github.com/extra2000/generic-box/commit/af7b53e0c805fe1edaba9c1014c0b13f9c6069cd))


### Documentations

* **README:** Add instruction to change to `--provider=virtualbox` if using [Oracle VM VirtualBox](https://www.virtualbox.org/) ([aee77fe](https://github.com/extra2000/generic-box/commit/aee77fefa92a68f1fe714b306baff22b2e098281))

## [1.2.0](https://github.com/extra2000/generic-box/compare/v1.1.1...v1.2.0) (2020-12-07)


### Features

* **Vagrantfile:** Allow creating multiple Vagrant files in `vagrant/` ([937dc08](https://github.com/extra2000/generic-box/commit/937dc0881b4575eb47f21b3f973190e5b4cf3061))

### [1.1.1](https://github.com/extra2000/generic-box/compare/v1.1.0...v1.1.1) (2020-11-28)


### Documentations

* **README:** Remove Travis CI badge ([4c406e0](https://github.com/extra2000/generic-box/commit/4c406e0726d4f602ae6c7dbe78b11cceae9dde38))


### Continuous Integrations

* **AppVeyor:** Add `semantic-release` ([3dedee7](https://github.com/extra2000/generic-box/commit/3dedee79bc7c41f21a61de4e4f565c0513faea60))
* Remove Travis CI because it is no longer free ([f5e0a3f](https://github.com/extra2000/generic-box/commit/f5e0a3fe76506f2f895dab3d50def4dc4dea1c46))

## [1.1.0](https://github.com/extra2000/generic-box/compare/v1.0.0...v1.1.0) (2020-11-25)


### Features

* **vagrant:** Add `aarch64` KVM for openSUSE families ([95039ef](https://github.com/extra2000/generic-box/commit/95039efeb66f065fe2c4f9b148d766c3b7aeadca))
* **vagrant:** Add Arch Linux `x86_64` ([516e1ea](https://github.com/extra2000/generic-box/commit/516e1ea016f18b0d62ba34e19181f1c7fe9f474e))
* **vagrant:** Add Debian 10 `x86_64` box ([671d9c7](https://github.com/extra2000/generic-box/commit/671d9c77953ac19c2619d5b76a95814222b7cb97))
* **vagrant:** Add Fedora 32 `x86_64` box ([8a25f22](https://github.com/extra2000/generic-box/commit/8a25f222b7c26e77893c144501fd1ac30b459fda))
* **vagrant:** Add openSUSE Leap 15.2 `aarch64` box ([9558ca2](https://github.com/extra2000/generic-box/commit/9558ca2f7956ce4766814c81a389ce2e3bc76238))
* **vagrant:** Add openSUSE Leap 15.2 `x86_64` box ([8e6a7d8](https://github.com/extra2000/generic-box/commit/8e6a7d8a258c8c71a2fd114d6d51ffa925fb11d7))
* **vagrant:** Add openSUSE Tumbleweed `aarch64` box ([1110fb4](https://github.com/extra2000/generic-box/commit/1110fb41165513e9235a4531a1223de7c680ed92))
* **vagrant:** Add openSUSE Tumbleweed `x86_64` box ([ff7069d](https://github.com/extra2000/generic-box/commit/ff7069dac019ede481d166f8ad219d8dbd15766a))
* **vagrant:** Add Ubuntu 20.04 `x86_64` box ([d29c777](https://github.com/extra2000/generic-box/commit/d29c7774ab998c87d691135885abcbe414f39813))


### Documentations

* **README:** Change item into BASH commands ([2cb4be0](https://github.com/extra2000/generic-box/commit/2cb4be083c8ea7668e3fe5d567fa3f71b41e4028))


### Code Refactoring

* Move Vagrant example files into `vagrant/examples/` directory ([d403fa4](https://github.com/extra2000/generic-box/commit/d403fa43f2ff759f8d7359a695e33e5d7dc04e87))
* Rename `generic-box.example` to `generic-box.centos-7.x86_64.example` ([d43cb89](https://github.com/extra2000/generic-box/commit/d43cb89110119ecdc283abd91273a5022ab17092))


### Fixes

* **vagrant/examples/Vagrantfile.generic-box.debian-10.x86_64.example:** Fix box unable to communicate with other boxes ([b5e1e99](https://github.com/extra2000/generic-box/commit/b5e1e997ca68c1ec66d553cbecde54615b75bdd7))
* **vagrant/examples/Vagrantfile.generic-box.opensuse*:** Fix box unable to communicate with other boxes ([61cb014](https://github.com/extra2000/generic-box/commit/61cb0140b2af7111d6bbd710421f4cf58ef7beeb))
* **vagrant/examples/Vagrantfile.generic-box.ubuntu-2004.x86_64.example:** Fix box unable to communicate with other boxes ([2bfaad5](https://github.com/extra2000/generic-box/commit/2bfaad58954da906187a01f42f75264ee51e30e2))


### Continuous Integrations

* **semantic-release:** Write version into `VERSION.txt` file ([be50997](https://github.com/extra2000/generic-box/commit/be50997649cbbe37d5654ec26d000890441e2fb3))


### Maintenance

* **release:** 1.0.1-alpha.1 [skip ci] ([199f03a](https://github.com/extra2000/generic-box/commit/199f03a788a0138868534065d4a61d24e43d0c00))
* **release:** 1.1.0-alpha.1 [skip ci] ([412bbe9](https://github.com/extra2000/generic-box/commit/412bbe92e58503ea8a1ecb344b6a41651c936101))
* **release:** 1.1.0-alpha.2 [skip ci] ([f786130](https://github.com/extra2000/generic-box/commit/f78613073b081e0d78a0a76b9f04ef152b278732))
* **release:** 1.1.0-beta.1 [skip ci] ([a7369d7](https://github.com/extra2000/generic-box/commit/a7369d7cb6e0fe229c4e6a9015d507d1502908b8))
* **release:** 1.1.0-beta.2 [skip ci] ([eb60112](https://github.com/extra2000/generic-box/commit/eb60112ff0ca3b0023c4d36ad558a43efe1b6cd1))
* **release:** 1.1.0-beta.3 [skip ci] ([3ced80c](https://github.com/extra2000/generic-box/commit/3ced80c2d1a0fd9ef24e2613e67a47807091c244))


### Styles

* **vagrantfiles:** Remove double spacing ([25d11d8](https://github.com/extra2000/generic-box/commit/25d11d85a525384137fc29435575da650d45c324))

## [1.1.0-beta.3](https://github.com/extra2000/generic-box/compare/v1.1.0-beta.2...v1.1.0-beta.3) (2020-11-25)


### Continuous Integrations

* **semantic-release:** Write version into `VERSION.txt` file ([be50997](https://github.com/extra2000/generic-box/commit/be50997649cbbe37d5654ec26d000890441e2fb3))

## [1.1.0-beta.2](https://github.com/extra2000/generic-box/compare/v1.1.0-beta.1...v1.1.0-beta.2) (2020-11-25)


### Features

* **vagrant:** Add Arch Linux `x86_64` ([516e1ea](https://github.com/extra2000/generic-box/commit/516e1ea016f18b0d62ba34e19181f1c7fe9f474e))

## [1.1.0-beta.1](https://github.com/extra2000/generic-box/compare/v1.0.0...v1.1.0-beta.1) (2020-11-16)


### Features

* **vagrant:** Add `aarch64` KVM for openSUSE families ([95039ef](https://github.com/extra2000/generic-box/commit/95039efeb66f065fe2c4f9b148d766c3b7aeadca))
* **vagrant:** Add Debian 10 `x86_64` box ([671d9c7](https://github.com/extra2000/generic-box/commit/671d9c77953ac19c2619d5b76a95814222b7cb97))
* **vagrant:** Add Fedora 32 `x86_64` box ([8a25f22](https://github.com/extra2000/generic-box/commit/8a25f222b7c26e77893c144501fd1ac30b459fda))
* **vagrant:** Add openSUSE Leap 15.2 `aarch64` box ([9558ca2](https://github.com/extra2000/generic-box/commit/9558ca2f7956ce4766814c81a389ce2e3bc76238))
* **vagrant:** Add openSUSE Leap 15.2 `x86_64` box ([8e6a7d8](https://github.com/extra2000/generic-box/commit/8e6a7d8a258c8c71a2fd114d6d51ffa925fb11d7))
* **vagrant:** Add openSUSE Tumbleweed `aarch64` box ([1110fb4](https://github.com/extra2000/generic-box/commit/1110fb41165513e9235a4531a1223de7c680ed92))
* **vagrant:** Add openSUSE Tumbleweed `x86_64` box ([ff7069d](https://github.com/extra2000/generic-box/commit/ff7069dac019ede481d166f8ad219d8dbd15766a))
* **vagrant:** Add Ubuntu 20.04 `x86_64` box ([d29c777](https://github.com/extra2000/generic-box/commit/d29c7774ab998c87d691135885abcbe414f39813))


### Documentations

* **README:** Change item into BASH commands ([2cb4be0](https://github.com/extra2000/generic-box/commit/2cb4be083c8ea7668e3fe5d567fa3f71b41e4028))


### Code Refactoring

* Move Vagrant example files into `vagrant/examples/` directory ([d403fa4](https://github.com/extra2000/generic-box/commit/d403fa43f2ff759f8d7359a695e33e5d7dc04e87))
* Rename `generic-box.example` to `generic-box.centos-7.x86_64.example` ([d43cb89](https://github.com/extra2000/generic-box/commit/d43cb89110119ecdc283abd91273a5022ab17092))


### Fixes

* **vagrant/examples/Vagrantfile.generic-box.debian-10.x86_64.example:** Fix box unable to communicate with other boxes ([b5e1e99](https://github.com/extra2000/generic-box/commit/b5e1e997ca68c1ec66d553cbecde54615b75bdd7))
* **vagrant/examples/Vagrantfile.generic-box.opensuse*:** Fix box unable to communicate with other boxes ([61cb014](https://github.com/extra2000/generic-box/commit/61cb0140b2af7111d6bbd710421f4cf58ef7beeb))
* **vagrant/examples/Vagrantfile.generic-box.ubuntu-2004.x86_64.example:** Fix box unable to communicate with other boxes ([2bfaad5](https://github.com/extra2000/generic-box/commit/2bfaad58954da906187a01f42f75264ee51e30e2))


### Maintenance

* **release:** 1.0.1-alpha.1 [skip ci] ([199f03a](https://github.com/extra2000/generic-box/commit/199f03a788a0138868534065d4a61d24e43d0c00))
* **release:** 1.1.0-alpha.1 [skip ci] ([412bbe9](https://github.com/extra2000/generic-box/commit/412bbe92e58503ea8a1ecb344b6a41651c936101))
* **release:** 1.1.0-alpha.2 [skip ci] ([f786130](https://github.com/extra2000/generic-box/commit/f78613073b081e0d78a0a76b9f04ef152b278732))

## [1.1.0-alpha.2](https://github.com/extra2000/generic-box/compare/v1.1.0-alpha.1...v1.1.0-alpha.2) (2020-11-15)


### Code Refactoring

* Move Vagrant example files into `vagrant/examples/` directory ([d403fa4](https://github.com/extra2000/generic-box/commit/d403fa43f2ff759f8d7359a695e33e5d7dc04e87))


### Fixes

* **vagrant/examples/Vagrantfile.generic-box.debian-10.x86_64.example:** Fix box unable to communicate with other boxes ([b5e1e99](https://github.com/extra2000/generic-box/commit/b5e1e997ca68c1ec66d553cbecde54615b75bdd7))
* **vagrant/examples/Vagrantfile.generic-box.opensuse*:** Fix box unable to communicate with other boxes ([61cb014](https://github.com/extra2000/generic-box/commit/61cb0140b2af7111d6bbd710421f4cf58ef7beeb))
* **vagrant/examples/Vagrantfile.generic-box.ubuntu-2004.x86_64.example:** Fix box unable to communicate with other boxes ([2bfaad5](https://github.com/extra2000/generic-box/commit/2bfaad58954da906187a01f42f75264ee51e30e2))

## [1.1.0-alpha.1](https://github.com/extra2000/generic-box/compare/v1.0.1-alpha.1...v1.1.0-alpha.1) (2020-11-05)


### Features

* **vagrant:** Add Debian 10 `x86_64` box ([671d9c7](https://github.com/extra2000/generic-box/commit/671d9c77953ac19c2619d5b76a95814222b7cb97))
* **vagrant:** Add Fedora 32 `x86_64` box ([8a25f22](https://github.com/extra2000/generic-box/commit/8a25f222b7c26e77893c144501fd1ac30b459fda))
* **vagrant:** Add openSUSE Leap 15.2 `aarch64` box ([9558ca2](https://github.com/extra2000/generic-box/commit/9558ca2f7956ce4766814c81a389ce2e3bc76238))
* **vagrant:** Add openSUSE Leap 15.2 `x86_64` box ([8e6a7d8](https://github.com/extra2000/generic-box/commit/8e6a7d8a258c8c71a2fd114d6d51ffa925fb11d7))
* **vagrant:** Add openSUSE Tumbleweed `aarch64` box ([1110fb4](https://github.com/extra2000/generic-box/commit/1110fb41165513e9235a4531a1223de7c680ed92))
* **vagrant:** Add openSUSE Tumbleweed `x86_64` box ([ff7069d](https://github.com/extra2000/generic-box/commit/ff7069dac019ede481d166f8ad219d8dbd15766a))
* **vagrant:** Add Ubuntu 20.04 `x86_64` box ([d29c777](https://github.com/extra2000/generic-box/commit/d29c7774ab998c87d691135885abcbe414f39813))


### Documentations

* **README:** Change item into BASH commands ([2cb4be0](https://github.com/extra2000/generic-box/commit/2cb4be083c8ea7668e3fe5d567fa3f71b41e4028))

### [1.0.1-alpha.1](https://github.com/extra2000/generic-box/compare/v1.0.0...v1.0.1-alpha.1) (2020-11-05)


### Code Refactoring

* Rename `generic-box.example` to `generic-box.centos-7.x86_64.example` ([d43cb89](https://github.com/extra2000/generic-box/commit/d43cb89110119ecdc283abd91273a5022ab17092))

## 1.0.0 (2020-10-10)


### Features

* Add salt/ ([0c80f0a](https://github.com/extra2000/generic-box/commit/0c80f0ae8c2986fa1969c021731deae3707ac6b9))
* Add Vagrant ([2af3a38](https://github.com/extra2000/generic-box/commit/2af3a3883b939c55ff566b31bf549968a2d1ed9d))


### Styles

* Add .gitignore ([e4a9bff](https://github.com/extra2000/generic-box/commit/e4a9bffc4af1801d44ccbf09d4f8ce940bd6980d))


### Continuous Integrations

* **travis:** Add Slack notifications ([05025f0](https://github.com/extra2000/generic-box/commit/05025f07abfa50d59b3dc40c3b912271057d5b0a))
* Add AppVeyor ([a5ac86a](https://github.com/extra2000/generic-box/commit/a5ac86a9471a5ff12cf441184cf11a723a65706e))
* Add Travis CI and semantic-release ([23da61b](https://github.com/extra2000/generic-box/commit/23da61b722d8c02aee6a595fb359a8765746cf20))


### Maintenance

* **release:** 1.0.0-alpha.1 [skip ci] ([d782ad4](https://github.com/extra2000/generic-box/commit/d782ad48addfd95dc787707ae40366811430579b))


### Documentations

* **README:** Add badges ([9815069](https://github.com/extra2000/generic-box/commit/9815069bd9241fd37eadb7442e0db615492d4de6))
* **README:** Add instructions ([d52a5f9](https://github.com/extra2000/generic-box/commit/d52a5f9c456bf02242ff7b1f93b81f81043c1161))

## 1.0.0-alpha.1 (2020-10-10)


### Features

* Add salt/ ([0c80f0a](https://github.com/extra2000/generic-box/commit/0c80f0ae8c2986fa1969c021731deae3707ac6b9))
* Add Vagrant ([2af3a38](https://github.com/extra2000/generic-box/commit/2af3a3883b939c55ff566b31bf549968a2d1ed9d))


### Styles

* Add .gitignore ([e4a9bff](https://github.com/extra2000/generic-box/commit/e4a9bffc4af1801d44ccbf09d4f8ce940bd6980d))


### Continuous Integrations

* **travis:** Add Slack notifications ([05025f0](https://github.com/extra2000/generic-box/commit/05025f07abfa50d59b3dc40c3b912271057d5b0a))
* Add AppVeyor ([a5ac86a](https://github.com/extra2000/generic-box/commit/a5ac86a9471a5ff12cf441184cf11a723a65706e))
* Add Travis CI and semantic-release ([23da61b](https://github.com/extra2000/generic-box/commit/23da61b722d8c02aee6a595fb359a8765746cf20))


### Documentations

* **README:** Add instructions ([d52a5f9](https://github.com/extra2000/generic-box/commit/d52a5f9c456bf02242ff7b1f93b81f81043c1161))
