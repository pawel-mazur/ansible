# Ansible playbooks

## Users

Bootstrap and configure ansible user

```
ansible-playbook -k -l server users.yaml
```

## Zabbix

Install and configure zabbix-agent package to the monitored server

```
ansible-playbook zabbix.yaml
```
