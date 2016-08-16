# Install Wordpress on Ubuntu using Ansible's playbook.

## Requirements
* Install the newest version of Ansible.
* Expect an Ubuntu instance server on AWS. 
* Change the values ansible_ssh_host and ansible_ssh_private_key_file on hosts file.
* Copy secrets_sample.yml to secret.yml and specify your secret keys.

## WordPress, Nginx PHP-FPM
Run the playbook as follows:
	
    ansible-playbook wp_nginx.yml

You should be able to view your WordPress site online at: http://your_server_ip.