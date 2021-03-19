# External Data Group Deployment with AS3 and Ansible
A Basic playbook that will allow to reference an external datagroup name "mydatagroup" and apply it to bigip
replace:
  <bigip_ip> : with your bigip ip address
  <username> : bigip username
  <password> : bigip password

run the command

ansible-playbook -i myinventory.yml as3_manual.yml
