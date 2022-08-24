# Vagrant
Vagrant - virtual machine environment, defined in code

## Running the example 

* Clone the repository and run `vagrant up` - this will setup the basic vagrant machine with tools installed for the course
* Uncomment the section containing `ansible.playbook = "playbooks/infrastructure.yml"` for the docker-compose infrastructure setup (*Repositories needed for it will be added further in the course*)
* Uncomment and add your AWS ID and AWS KEY inside `playbooks/init.yml` for AWS CLI configuration
* Run the `vagrant provision` on running machine for update  

## Modifying the vagrant:
* Change the `git_repository` and `git_branch` variables to point our vagrant to repositories you have created for quick validation of your work.