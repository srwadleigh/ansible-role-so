# ansible-roles-so

A simple role to assist with the initial setup of stack orchestrator

 - https://github.com/cerc-io/stack-orchestrator/

## Task Configuration

```
- name: Setup stack orchestrator
  hosts: somehost
  become: true
  roles:
    - role: so
```

## Deployment

```
ansible-playbook -i hosts site.yml --tags=so --limit=somehost
```
