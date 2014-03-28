boot2docker Vagrant Box
==================
...for Windows/Putty.

Built on https://github.com/mitchellh/boot2docker-vagrant-box

## Steps
### Start the VM
* Install Virtual Box and Vagrant
* Download [v0.5.4-1/boot2docker_virtualbox.box](https://github.com/mitchellh/boot2docker-vagrant-box/releases/download/v0.5.4-1/boot2docker_virtualbox.box) to _THIS-PROJECT_/../v0.5.4-1/
* Checkout this project
* `vagrant up`

### Setup [Putty](https://puttytray.goeswhere.com/)
* Click Keygen
* Load C:/Users/_username_/.vagrant.d/insecure_private_key
* Save private key as C:/Users/_username_/.vagrant.d/docker.ppk

### Login
* Host: 127.0.0.1
* Port: 2222
* Username: docker
* Private key: C:/Users/_username_/.vagrant.d/docker.ppk