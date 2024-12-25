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
