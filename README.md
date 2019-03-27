# Ansible
Host file resides in /etc/ansible/hosts
Update the developers block with the server IP's, its ssh pem key, ssh user and the port

Make a directory and place main.yml in there. After that run the following command which will create the users and give the proper shells.
```
$ ansible-playbook main.yml
```
