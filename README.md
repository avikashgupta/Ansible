# This playbook will allow the ansible user to create a passwordless ssh connection with the worker nodes.
Use the below command to run this playbook:

$ ansible-playbook sshpwdless.yml

Here worker node has a IP: 192.168.56.12, you can use the IP's of multiple nodes in a loop to perform this task on all the servers working under ansible controller.
