1. Install Ansible: https://docs.ansible.com/ansible/latest/installation\_guide/intro\_installation.html#installing-ansible-on-ubuntu
  1. sudo apt update
  1. sudo apt install software-properties-common
  1. sudo apt-add-repository --yes --update ppa:ansible/ansible
  1. sudo apt install ansible
2. Install Requirements:
  2. `$ ansible-galaxy role install -r requirements.yml`
3. Run the playbook:
  3. `$ ansible-playbook bootstrap-vm.yml`

At this stage you will have docker and kubernetes installed.  
Unfortunately, kubernetes will be configured for root, so you may want to copy the config to other uses.

