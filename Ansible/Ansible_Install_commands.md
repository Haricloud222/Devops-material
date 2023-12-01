

# how to run ansible shell command 
#  to check the ram utilization 

- ansible all -i hosts -m shell -a "free -m"


# how to run ansible shell command 
#  to check the disk  utilization 

- ansible all -i hosts -m shell -a "df -h"


# how to run ansible playbooks
- ansible-playbook -i "hosts" "file.yml"

example : 

1)  ansible-playbook -i hosts httpd_yum.yml

2)  ansible-playbook -i hosts docker.yml


# Refer to documentation
https://docs.ansible.com/ansible/latest/collections/ansible/builtin/yum_module.html
