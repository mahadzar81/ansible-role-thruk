# Ansible Role: Thruk

## Installation
Use ansible-galaxy command to download this repository to the system that will run this playbook.

```
ansible-galaxy install mahadzar81.thruk
```

## Requirements

No special requirements; note that this role requires root access, so either run it in a playbook with a global `become: true`, or invoke the role in your playbook like:

```
- name: "Provision Thruk server"
  hosts: all
  gather_facts: yes
  become: true
  roles:
    - { role: thruk }

```
