# genesis-vagrant

> Automagic up vagrant

## Minimal dependencies

* [Vagrant](https://www.vagrantup.com/downloads.html)
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

### OSX

```sh
❯ brew update
❯ brew install vagrant
❯ brew install virtualbox
```

### Linux

*In progress*

### Window

*In progress*

## Usage

```
❯ git clone https://github.com/92bondstreet/genesis-vagrant.git
# curl -sL https://github.com/92bondstreet/genesis-nginx/archive/master.tar.gz | tar xz
❯ cd genesis-vagrant
❯ vagrant up
❯ vagrant ssh
```

## Mirror (from scratch)

List of available base boxes: [http://www.vagrantbox.es/](http://www.vagrantbox.es/)

```sh
❯ vagrant box add https://atlas.hashicorp.com/ARTACK/boxes/debian-jessie
❯ vagrant init ARTACK/debian-jessie
❯ vagrant up
```

## destroy?

```sh
❯ vagrant global-status
❯ vagrant destroy box_id
```

## Deep diving

* [Creating a Custom Vagrant Box](http://williamwalker.me/blog/creating-a-custom-vagrant-box.html)
* [Getting started with Vagrant](http://adamenger.com/blog/2014/02/18/getting-started-with-vagrant/)
* [How to use Vagrant for local web development](http://blog.osteel.me/posts/2015/01/25/how-to-use-vagrant-for-local-web-development.html)
