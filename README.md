# gke-ansible-playbook
Ansible playbook to upload a gke cluster.

## Requirements
**You need to install the collection google.cloud .**
```
ansible-galaxy collection install google.cloud
```

**The below requirements are needed on the host:**
```
python >= 2.6
requests >= 2.18.4
google-auth >= 1.3.0
```

## Command to run the playbook
```
ansible-playbook ./ansible-playbook/create-cluster.yaml -i localhost
```
