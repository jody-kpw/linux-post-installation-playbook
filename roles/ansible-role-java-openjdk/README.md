Role Name
=========

Ansible Role Java OpenJDK

Requirements
------------

This role requires Ansible 2.4 or higher, and platform requirements are listed in the metadata file.

Role Variables
--------------

#### Available variables are listed below.

default values (see `defaults/main.yml`):

Set to true to install the following packages.
```
java_enabled: true
```

# Set java_packages if you would like to use a different version than the
# default (OpenJDK 1.8).
```
java_packages: java-1.8.0-openjdk
```

**Alternatively you can assign at group_vars.**

Dependencies
------------

None.

Example Playbook
----------------
```
- hosts: servers
  become: true
  roles:
     - ansible-role-java-openjdk
```

License
-------

GPLv2

Author Information
------------------

* Author: Jody WAN
* Linkedin: https://www.linkedin.com/in/jodywan/
* Wsebsite: https://www.jodywan.com
