# devops-ansible-playbook

Added devops Ansible playbooks :-->

1) Cassandra
2) Elasticsearch
3) Sonarqube
4) Nginx
5) Mysql
6) Java8
7) Docker
8) AWS SSM agent

## Command to run all playbooks on all hosts
```console
foo@bar:~$ ansible-playbook -i inventory install-all-roles.yml
```

## Command to run specific playbook on all hosts
```console
foo@bar:~$ ansible-playbook -i inventory install-all-roles.yml --tags aws-ssm
```

## Command to run specific playbook on specific host
```console
foo@bar:~$ ansible-playbook -i inventory install-all-roles.yml --tags aws-ssm --limit localhost
```
