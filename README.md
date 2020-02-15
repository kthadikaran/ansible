# Ansible
This repository will discuss about Ansible Ad-hoc commands and Ansible Playbooks

Ansible is a free and opensource automation tool which is enables you to manage and control multiple servers from one central location.

Ansible uses YAML (Yet Another Markup Language) in its configuration and automation jobs which are human-readable and quite easy to follow. YAML uses SSH protocol to communicate with remote servers, unlike other automation platforms that require to you install an agent on remote nodes to communicate with them.

A playbook is a set of instructions which is called as task or play that define how tasks are to be executed on remote hosts or a group of host machines. 


Ansible playbook for beginner

If you’re new to YAML, the syntax can be tricky at first, particularly with spacing (no tabs). Before running a playbook, you can check the syntax using:

$ansible-playbook --syntax-check myplaybook.yml

You can test a playbook without actually making any changes to the target hosts:

$ansible-playbook --check myplaybook.yml

Stepping through a playbook may also be useful

$ansible-playbook --step myplaybook.yml



 
