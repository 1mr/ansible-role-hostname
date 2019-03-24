Hostname
========
[![Build Status](https://travis-ci.com/1mr/ansible-role-hostname.svg?branch=master)](https://travis-ci.com/1mr/ansible-role-hostname)

This role helps to set hostname.

Requirements
------------

This role requires ansible 1.4 or higher.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: 1mr.hostname, tags: hostname }

License
-------

BSD
