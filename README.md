# Ansible Repo

This repo contains all Ansible scripts for network servers.

## Scope

### Bootstrap

Ansible will not handle OS installation and ssh key will be copied to allow playbook to run. Bootstrap playbooks will setup baseline host settings. This includes required packages, required services, and baseline settings.

### Roles

Using the inventory to create groups, roles will be assigned for each Ansible managed device.

### Updates

Updates will be automated based on groups.
