
Hi ALL

You can user this ansible scrip to get undestand how it works with AWS

ansible-aws-examples
====================

Example playbooks to launch AWS infrastructure.

Steps:

1. Edit var/aws-creds.yml to include your own AWS credentials
2. Edit var/dev-environment.yml to define the security groups,
   sets of instances, etc, that will be used.
3. Run: ansible-playbook -i hosts provision.yml

In case do you want to remove(shutdown) this instance 

setthe exact_count values in the vars/dev-environment.yml file to 0 and re-running provision.yml.
