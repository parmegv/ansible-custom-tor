[![Build Status](https://travis-ci.org/parmegv/ansible-custom-tor.svg?branch=master)](https://travis-ci.org/parmegv/ansible-custom-tor)

Role Name
=========

Compiles a custom version of Tor synced from the control machine.

Requirements
------------

Ansible version >=2.2

Role Variables
--------------

	tor_dirname: "tor" # Directory name of the Tor sources
	src_dirpath: "./" # Directory in the local machine where the custom Tor sources are
	dest_dirpath: "~/" # Directory in the target machine where the custom Tor sources will be placed

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

	- hosts: localhost
	  roles:
      - { role: ansible-custom-tor, tor_dirname: "tor/", src_dirpath: "./" }

License
-------

BSD

Author Information
------------------

Rafael Gálvez Vizcaíno
Ph.D. student at ESAT/COSIC KU Leuven
