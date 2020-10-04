# osdev
## setup（macos）
* vagrant を使う
``` bash
$ brew cask install vagrant
# https://app.vagrantup.com/debian/boxes/jessie64
$ vagrant init debian/jessie64
$ vagrant up
$ vagrant ssh
```

* ```vagrant ssh``` から
``` bash
$ sudo apt-get update
$ sudo apt-get install -y git build-essential nasm
```
