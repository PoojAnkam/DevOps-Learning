# DevOps-Learning
Vertex techosys 

Ansible
---
- hosts: all
  become: yes
  tasks:
          - name: install apache2
            apt:
                    name: apache2
                    state: present


