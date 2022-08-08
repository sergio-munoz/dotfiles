# dotfiles
PubNub Dotfiles


## Ansible Playbook

```
ansible-playbook dotfiles_mgmt.yml -i inventory -e "@group_vars/local.yml" -t install,present
```
