# Ansible Role: Thruk

## Requirements

No special requirements; note that this role requires root access, so either run it in a playbook with a global `become: true`, or invoke the role in your playbook like:

- name: "Provision Thruk server"
  hosts: all
  gather_facts: yes
  become: true
  roles:
    - { role: thruk }