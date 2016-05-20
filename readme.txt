Steps to setup an OSA lab environment using cloud instances.  Please execute the following playbooks in the order below.

/lab-environment
ansible-playbook -i hosts target-create.yml
ansible-playbook -i hosts admin-create.yml
ansible-playbook -i hosts base-users.yml

/rpcv12-cloud-region
ansible-playbook -i hosts all.yml
ansible-playbook -i hosts prep_deploy.yml
ansible-playbook -i hosts build.yml
