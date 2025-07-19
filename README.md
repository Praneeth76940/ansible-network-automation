# Cisco Network Automation with Ansible

This project automates the configuration of Cisco routers using Ansible playbooks.  
We push loopback interface configurations to multiple routers using SSH.

## Files:
- inventory.ini: List of Cisco devices
- push_config.yml: Ansible playbook that pushes the config

## How to Run:
```bash
ansible-playbook -i inventory.ini push_config.yml
