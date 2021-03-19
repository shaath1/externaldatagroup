## External Data Group Deployment with AS3 and Ansible
On the setup file change values in the setup.yml to reflect to your enviroment you will need to add:
admin username
admin passowrd
bigip address (could be hostname or IP)

### f5devcentral.atc_deploy
Run this command:  
 ansible-playbook -i myinventory.yml playbook_f5devcentral_atc_deploy.yml

### uri
Run this command:  
 ansible-playbook -i myinventory.yml playbook_uri.yml 
