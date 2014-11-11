INFO-6016 Dev Environment
Requirements

	Vagrant (with Virtual Box)
	Ansible

Install Vagrant for Local Development

	1. Download Virtual Box to machine

		https://www.virtualbox.org/wiki/Downloads

	2. Download Vagrant

		www.vagrantup.com/downloads.html 

	3. cd to cloned folder.

		vagrant up

	9. SSH into your machine

		vagrant ssh

## Ports

Redis port:

    127.0.0.1:7421

HTTP (with ssl)

    http://127.0.0.0.1:5443

HTTP (without ssl)

    http://127.0.0.0.1:5656

MySQL

    127.0.0.0.1:9234

	name: root
	password: info6016
