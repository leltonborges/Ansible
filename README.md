# Estudo de Ansible

![GitHub repo size](https://img.shields.io/github/repo-size/leltonborges/Ansible)
![repo study](https://img.shields.io/badge/dev-study-green)

## Dependencias
* [Python 2.7](https://www.python.org/)
* Python-apt
* [ansible v10](https://docs.ansible.com/)

## Execução

### Execute
```ansible
ansible-vault create pass.yml
```
coloque a senha no arquivo _**.mypass_vault**_ e execute
```ansible
ansible-playbook --vault-password-file=.mypass_vault install.yml 
```