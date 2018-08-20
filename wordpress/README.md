# Wordpress

This playbook installs a full Wordpress Stack (Apache+PHP, MySQL and Wordpress) on a single server.

To build the Wordpress server, edit hosts file and replace worpress_server_ip with the ip of the server where you want to install Wordpress.

To run the playbook, just type

	ansible-playbook playbook.yml -i hosts -u <username> --ssh-extra-args="-i <ssh key location>" 	
