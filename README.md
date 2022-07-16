My Personal Ansible Roles
===============

# How to use
0. sudo apt-get install sshpass
1. List your hosts in **hosts** file
2. Edit roles which you want to install in target.yml
3. Run `ansible-playbook -i hosts roles_playbook.yml -u root -k`

## 1/ Check your syntax before running

```bash
ansible-playbook --syntax-check targets.yml
```

```run
ansible-playbook -i hosts roles_playbook.yml -u root -k
pass: k1etMinkyApp
```