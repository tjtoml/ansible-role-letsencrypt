[![Build Status](https://travis-ci.org/tjtoml/ansible-role-letsencrypt.svg?branch=master)](https://travis-ci.org/tjtoml/ansible-role-letsencrypt) [![role](https://img.shields.io/badge/Galaxy-tjtoml.letsencrypt-5bbdbf.svg)](https://galaxy.ansible.com/tjtoml/letsencrypt/)

 tjtoml.letsencrypt
=========

This role installs `certbot`, the command line client for the letsencrypt project. This role is intended as a building block and only serves to make the `certbot` command available. 

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: webservers
      roles:
         - { role: tjtoml.letsencrypt }

License
-------

BSD, MIT
