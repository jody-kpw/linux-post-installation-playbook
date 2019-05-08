Role Name
=========
rh-python36 - A release of Python 3.6 with a number of additional utilities. This Software Collection gives developers on CentOS and RHEL access to Python 3.6 and allows them to benefit from various advantages and new features of this version. The rh-python36 Software Collection contains Python 3.6 interpreter, a set of extension libraries useful for programming web applications and mod_wsgi (only supported with the httpd24 Software Collection), PostgreSQL database connector, and numpy and scipy.

Requirements
------------

This role requires Ansible 2.4 or higher, and platform requirements are listed in the metadata file.

Dependencies
------------

None.

Role Variables
--------------

#### Available variables are listed below.

default values (see `defaults/main.yml`):

Set to true to install the following packages.
```
python36_enabled: false
```

Example Playbook
----------------
```
  - hosts: servers
    become: true
    roles:
       - ansible-role-python36
```

License
-------

GPLv2

Author Information
------------------

* Author: Jody WAN
* Linkedin: https://www.linkedin.com/in/jodywan/
* Wsebsite: https://www.jodywan.com
