#run the playbook using
ansible-playbook -i inventory/hosts provision.yml

# you need to determine your hosts in inventory/hosts
# you need to detrmine your zabbix server in roles/provision/vars/main.yml
# all the rest of the important task is in roles/provision/tasks/main.yml
# for Red Hat base distro you can modify your condition in above line ...
