#Deploying a base Freebsd configuration. 

This will take a vanilla freebsd system and install and configure:

Software:
  - postfix
  - bind
  - zfs snapshot tools  - need to get the exact name

Installation

    Install python3 or higher
    Run $ ansible-galaxy install -r requirements.yml inside this directory to install required Ansible roles.
    Run ansible-playbook main.yml -i inventory -K inside this directory. Enter your account password when prompted.

