# automation-with-ansible

Here we are using ansible to deploy 3 webservers and a haproxy which is acting as a load balancer along with a bastionhost(which is used for security)

The following steps are to be followed for the servers to work as expected:

Create a keypair using your public ssh key in citycloud
Using this keypair create 5 servers (3 for webservers, one for bastion host and the other one for haproxy)
Now modify the config file (ssh config) with the ip addresses of your servers and the ssh private key path
Now pull the files from git and execute the ansible playbook command
