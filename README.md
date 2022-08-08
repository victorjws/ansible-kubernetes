# ansible-kubernetes
Installing kubernetes using ansible

## Usage
### Install
1. Configure `hosts.yaml`
2. Execute ansible command
```shell
ansible-playbook -i hosts.yaml install.yaml
```
### Uninstall
1. Execute ansible command
```shell
ansible-playbook -i hosts.yaml reset.yaml
```
