# vmware_tag_vm
 
Ansible playbook to create a tag on an existing VM.  
  
## Usage
  
Create a creds.yml file using Ansible Vault:  
```
ansible-vault create creds.yml
username: { your_vcenter_username }
password: { your_vcenter_password }
```
  
Set tag and vm_name variables in group_vars or other Ansible variable location.  

