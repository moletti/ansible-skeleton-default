Ansible skeleton role: default
=========

Usage
------------
```
git clone git@github.com:moletti/ansible-skeleton-default.git ~/.ansible/skeleton/default
```

```
# Create role with custom skeleton
ansible-galaxy role init some-role --role-skeleton ~/.ansible/skeleton/default
```
or you can set the role_skeleton variable via ansible.cfg 

```bash
cat <<EOT >> ~/.ansible/ansible.cfg
[galaxy]
role_skeleton=~/.ansible/skeleton/default
EOT
```

```bash
ansible-galaxy role init ansible-role-some
```


LICENSE
-------
[MIT](/LICENSE)