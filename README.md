# How to use ansible

- Install ansible

```sh
apt install ansible -y
```

- Clone git

```sh
mkdir -p /var/lib/ansible
cd /var/lib/ansible
git clone https://github.com/rendyproklamanta/ansible-apps.git .
```

- Change variables

```sh
nano ubuntu/setup/vars.yml
```

- Change import file based on your OS Version

```sh
nano ubuntu/setup/main.yml
```

- Step to setup new server with docker deployment

```sh
ansible-playbook /var/lib/ansible/ubuntu/docker/main.yml
ansible-playbook /var/lib/ansible/ubuntu/setup/main.yml
```

- Deploy ansible security

```sh
ansible-playbook /var/lib/ansible/ubuntu/security/main.yml
```
