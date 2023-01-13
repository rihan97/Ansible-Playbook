# Ansible project
## A quick Ansible playbook installing prerequisites softwares on the instance

### Ansible Playbooks
Ansible playbooks is Ansible's orchestration language where we define what we want ansible to do, its a set of instructions like running commands in a sequence or more complex deployments and configs.
How are they written? In yaml format 
Playbook - a single yaml file
	Play - defines a set of activities
	Host - is defined on the play level
	(tasks) to be run on hosts
			Tasks - an action to be performed on the host
	            • Execute a command
	            • Run a script 
	            • Install a package 
	            • Shutdown / restart
			 
			 
Modules - the different actions run by tasks are called modules.
There are hundreds of them available on the ansible website or you can run command the following commond: ansible-doc -l
 

**Before automating with ansible its important to understand what you are trying to automate? If its an application what are its different components? And how does everything work together without the automation?**



