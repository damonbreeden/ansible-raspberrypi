# ansible-bootstrapDebian10
 Use these playbooks to bootstrap a Debian 10 or Ubuntu 18.04/20.04 server

 first run (asks for ssh connection password and installs your ssh key): ansible-playbook -k -u <username> -i inventory.yml ansible/ssh-keys.yml

or install everything: ansible-playbook -K -i inventory.yml *.yml # add '-k -u <username>' if haven't installed ssh keys above