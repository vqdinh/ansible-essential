<h2>Ansible Essential</h2>
Preparing Lab:

Install Virtualbox, extentions

Install vagrant

1. config inventory
2. Ansible addhoc (https://docs.ansible.com/ansible/latest/user_guide/intro_adhoc.html)
3. 



Ansible addhoc
ansible all -m ping -i investory
ansible host1 -m ping -i investory
ansible host1 -a 'ls -la' -i investory
ansible all -m shell -a 'ls -ll' -i investory
ansible all  -m copy -a "src=/etc/hosts dest=/tmp/hosts" -i investory



Ansible Inventory (https://docs.ansible.com/ansible/latest/user_guide/intro_inventory.html)

apt module:
https://docs.ansible.com/ansible/latest/modules/apt_module.html#parameter-state

ansible-playbook -i investory nginx_uninstall.yml
ansible-playbook -s first-example.yml -i investory



