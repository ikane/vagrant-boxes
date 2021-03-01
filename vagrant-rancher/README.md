https://journaldunadminlinux.fr/tutoriel-deployez-facilement-un-cluster-kubernetes-avec-rancher/


## Install docker

```
$ curl -fsSL https://get.docker.com -o get-docker.sh
$ sudo sh get-docker.sh

sudo usermod -aG docker vagrant
```

# Misc
https://github.com/hashicorp/vagrant/issues/12084

https://www.devopsroles.com/vagrant-no-virtualbox-guest-additions-installation-found-fixed/

```
vagrant plugin uninstall vagrant-vbguest
vagrant plugin install vagrant-vbguest --plugin-version 0.21
```
