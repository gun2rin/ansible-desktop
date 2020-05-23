**Ansible 2.9.6 playbook for Ubuntu 20.04 64bit**
=========

Simple playbook for Compo developers desktops.
Installs nginx, php-fpm, mysql, node.js, python, angular-cli, composer, Komodo, PhpStorm, Gimp, Peek, 
Inkscape, skype, google-chrome and some libraries.

`git clone git@github.com:gun2rin/ansible-desktop.git`

**Ansible installation.**

```sh
 sudo apt install ansible
 ```
https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-ubuntu
 
Edit **desktop.yaml**. Specify your settings like php version, username, db pass etc. if necessary.
 
**Play it**

```sh
cd ansible-desktop
sudo ansible-playbook desktop.yaml
```


 
 
 
 
 
