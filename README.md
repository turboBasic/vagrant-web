Vagrant+Ansible: provision site using single Ansible playbook with multiple roles
=================================================================================

- Vagrant creates one host in Virtualbox

- There is only one playbook per host

- Playbook contains multiple roles which are applied to a host in a sequence:

   - Apache
   - PHP

