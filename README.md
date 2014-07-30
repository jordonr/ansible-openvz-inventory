ansible-openvz-inventory
========================

Ansible inventory plugin for openvz hosts and guests

Inspired by libvirt_lxc.py inventory script
https://github.com/ansible/ansible/blob/e5ef0eca03cbb6c8950c06dc50d0ca22aa8902f4/plugins/inventory/libvirt_lxc.py 

Groups are determined by the description field of openvz guests
multiple groups can be seperated by commas: webserver,dbserver
