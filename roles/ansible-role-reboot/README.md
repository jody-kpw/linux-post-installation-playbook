Role Name
=========

ansible-role-reboot

Requirements
------------

This role requires Ansible 2.4 or higher, and platform requirements are listed in the metadata file.

Role Variables
--------------

#### Available variables are listed below.

default values (see `defaults/main.yml`):

reboot_enabled: false

Dependencies
------------

None.

Example Playbook
----------------
```
  - hosts: servers
    become: true
    roles:
       - ansible-role-reboot
```

License
-------

GPLv2

Author Information
------------------

* Author: Jody WAN
* Linkedin: https://www.linkedin.com/in/jodywan/
* Wsebsite: https://www.jodywan.com
