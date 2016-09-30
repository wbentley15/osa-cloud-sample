#Current support for OpenStack releases:

**Liberty	/rpcv12-cloud**</br>
**Mitaka	/rpcv13-cloud**

Click here for [installation instructions](https://github.com/wbentley15/osa-cloud-sample/blob/master/instructions.txt)


###Optional Steps:

Steps to setup an OSA lab environment using cloud instances.  Please execute the following playbooks in the order below.

	/lab-environment
	ansible-playbook -i hosts target-create.yml
	ansible-playbook -i hosts admin-create.yml
	ansible-playbook -i hosts base-users.yml



