# NAS-ANSIBLE-DOCKER

## Ansible

### Installation

[Documentation](https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html#installing-ansible-on-ubuntu)

```bash
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo add-apt-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
```

```bash
ansible-playbook -i hosts.ini <palybook> 
```