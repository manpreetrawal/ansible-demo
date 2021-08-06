# ansible-demo
#This repository is to perform below tasks on CentOS remote VM.

# Below re the 4 roles, you can run one or all roles

Roles: 
1) MySQL
2) Install Packages
3) Copy Repo
4) Install Tomcat

# To install all tasks run below command 
ansible-playbook link.yml -i hosts_node

# To Install one role
ansible-playbook -i hosts_node --tags $ROLE_NAME link.yml
