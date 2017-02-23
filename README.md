[![Build Status](https://travis-ci.org/parmegv/ansible-custom-tor.svg?branch=master)](https://travis-ci.org/parmegv/ansible-custom-tor)

Role Name
=========

Compiles a custom version of Tor synced from the control machine.

Requirements
------------

Ansible version >=2.2

Role Variables
--------------

	src_dir: "~/tor" # Directory (both in the local and the remote machines) where the custom Tor sources will are or will be placed

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

	- hosts: localhost
	  roles:
	  - { role: ansible-custom-tor, src_dir: "./tor" }

License
-------

BSD

Author Information
------------------

Rafael Gálvez Vizcaíno
Ph.D. student at ESAT/COSIC KU Leuven
