# Fedora Dev Setup


## Instalação do ansible

```bash
sudo dnf install ansible
```

## Download do playbook

```bash
git clone https://github.com/xcommerceweb/fedora-dev-setup.git
```

## Execução do playbook

```bash
ansible-playbook fedora-dev-setup/setup_workstation.yml  -e "local_user=yourusername" --ask-become-pass
```
