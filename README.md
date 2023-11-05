# Ansible

Commandds to run a Ansible playbook.
- ansible-playbook filename.yml

if your file is encrypted using vault then.
- ansible-playbook --ask-vault-pass filename.yml

To edit a encrypted file use
- ansible-vault edit filename.yml

To create a directory structure use.
- ansible-galaxy init rolename          ######### Best practice is to create inside your roles directory##########
