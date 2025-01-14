# How to use ansible

- Install ansible

```sh
apt install ansible -y
```

- Create dir for ansible

```sh
mkdir -p /var/lib/ansible
```

- Clone git

```sh
cd /var/lib/ansible
git clone https://github.com/rendyproklamanta/ansible-apps.git .
```

- Run ansible

```sh
ansible-playbook filename.yml
```

- Step to setup new server wih docker deployment

```sh
ansible-playbook ubuntu/docker/main.yml
ansible-playbook ubuntu/setup/main.yml
ansible-playbook ubuntu/security/main.yml
```
