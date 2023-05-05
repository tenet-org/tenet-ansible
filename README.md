
### 1) Setup hosts
Set IP address ```ansible-host``` in [hosts.yml](./hosts.yml) file


### 2) Setup stage configuration
Choose correct ```config_url``` filed in [deploy-node.yml](./deploy-node.yml)

#### Optional
If you want to sync your node from snapshot: enable ```sync_by_snapshot``` in [deploy-node.yml](./deploy-node.yml)

### 3) Deploy node
```
ansible-playbook -i hosts.yml deploy-node.yml
```
