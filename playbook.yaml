---
## playbook to install a package

- hosts: all
  gather_facts: no
  tasks:
    - name: "install htop"
      tags:
        - packages
      apt:
        state: present
        pkg:
          - htop
