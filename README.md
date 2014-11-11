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

    localhost:7421

HTTP (with ssl)

    https://localhost:5443

HTTP (without ssl)

    http://localhost:5656

MySQL

    localhost:9234

    name: root
    password: info6016
