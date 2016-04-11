# hadoop-using-ansible
This ansible playbook helps you to setup hadoop on local machine in hadoop in pseudo-distributed mode.

## Usage:
Setting up hadoop in Pseudo-Distributed using this playbook is easy.

1. Modify `ansible-hosts` file to add your host or list of hosts on which you want to install hadoop.
   
 	`#192.68.0.100 ansible_ssh_user=myusername ansible_ssh_pass=mypassword ansible_sudo_pass=q`
	  
     Modify the remote hostname or ip, username, password and sudo password.

2. Run playbook setup.yml using 
   `ansible-playbook -vvvv -i ansible-hosts setup.yml`
   

