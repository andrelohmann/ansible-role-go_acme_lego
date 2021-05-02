go-acme/lego
============

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-go_acme_lego.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-go_acme_lego)

Use this role to install [go-acme/lego](https://github.com/go-acme/lego).

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    lego_version: 4.3.1 #defaults to 'latest'

Example Playbook
----------------

    - hosts: lego
      roles:
         - andrelohmann.go_acme_lego

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
