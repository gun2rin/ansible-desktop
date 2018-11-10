**Ansible 2.7 playbook for Ubuntu 64bit**
=========

Simple playbook for Compo developers desktops.
Installs nginx, php-fpm, mysql, node.js, python, bower, gulp, angular-cli, composer, Komodo, PhpStorm, Gimp, Peek, 
Inkscape, skype, google-chrome and some libraries.

`git clone git@github.com:gun2rin/ansible-desktop.git`

**Ansible installation.**

```sh
 sudo apt-get update
 sudo apt-get install software-properties-common
 sudo apt-add-repository ppa:ansible/ansible
 sudo apt-get update
 sudo apt-get install ansible
 ```
https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#latest-releases-via-apt-ubuntu 
 
Edit **desktop.yaml**. Specify your settings like php version, username, db pass etc. if necessary.
 
**Play it**

```sh
cd ansible-desktop
sudo ansible-playbook desktop.yaml
```


 
 
 
 
 