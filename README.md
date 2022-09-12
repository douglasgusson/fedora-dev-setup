# 


## Instalação do ansible

```bash
sudo dnf install ansible
```

## Execução do playbook

```bash
ansible-playbook setup_workstation.yml --ask-become-pass
```

ou

```bash
ansible-playbook setup_workstation.yml -K
```

