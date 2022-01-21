# To launch
You need to create a folder.ssh, in the user.
Path: `/home/username/.ssh/`, this folder can be created with the command `mkdir ~/.ssh`
Next, go to the folder copy the private key from your server there. 

P.S. Don't forget to add permissions with the command `chmod 0600 key.pem`, where key is the name of your key.

# Task number zero
Write Ansible playbook for Nginx web server configuration, which will also configure firewall rules by opening ports 22, 80, 443

## Ansible config file & hosts.txt 
In Ansible.cfg, I recorded the configuration data:

Where is the hosts file, and so that there is no check at the beginning of each playbook.

## Ansible playbook

Description of ansible playbooks

### Firs playbook is "playbook_Nginx.yml"
The nginx web server is installed and started in it.

### Second playbooks is "playbook_FirewallRules.yml
In this playbook, a firewall is installed and rules are prescribed.

