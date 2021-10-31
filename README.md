# hadoop-using-ansible

This projet was created when I was newbie to both Hadoop and Ansible. This playbook was created to automate the process to setup hadoop cluster for testing purpose.

I remember setting up Hadoop clusters for version 2.7.1 using this playbook.

# Setup hadoop in pseudo-distributed mode using Ansible
This ansible playbook helps you to setup hadoop on local machine in hadoop in pseudo-distributed mode.

## Usage:
Setting up hadoop in Pseudo-Distributed using this playbook is easy.

1. Modify `ansible-hosts` file to add your host or list of hosts on which you want to install hadoop.
   
 	`#192.68.0.100 ansible_ssh_user=myusername ansible_ssh_pass=mypassword ansible_sudo_pass=<sudo_passwd>`
	  
     Modify the remote hostname or ip, username, password and sudo password.

2. Run playbook setup.yml using 
   `ansible-playbook -vvvv -i ansible-hosts setup.yml`
   

