# ansible-k8s
Ansible roles and playbooks for deploying a kubernetes cluster to Ubuntu VMs

# Requirements

```
ansible-galaxy install -r requirements.yml
```

# Test

```
ansible-playbook -i hosts.yml deploy_cluster site.yml 
```