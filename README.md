
### 1) Setup hosts
Set IP address ```ansible-host``` in [hosts.yml](./hosts.yml) file


### 2) Setup sync configuration
Set ```sync_by_snapshot``` filed in [deploy-node.yml](./deploy-node.yml)

### 3) Deploy node
```
ansible-playbook -i hosts.yml deploy-node.yml
```
