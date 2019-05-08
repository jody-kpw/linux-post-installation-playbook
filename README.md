# Linux Post-Installation

This playbook contains things to do after minimal CentOS 7 Installation. if you need to add an extra ansible role to it, feel free to modify or add anything.

### Review and update group_vars
```
group_vars/all.yml
And
initial.yml
```

###  Update inventory file hosts
```
inventory/hosts
```

#### Run Ansible Playbook
```
ansible-playbook initial.yml -i inventory/hosts
```
