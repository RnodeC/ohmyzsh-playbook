RnodeC OhMyZsh playbook
=========

Quickly and simply install ohmyzsh on a new machine.  A great way to get started (and stay consistent when jumping between machines)

Variables
---------
- `zsh_plugins`: space separated list of ohmyzsh plugins to include
- `zsh_theme`: the zsh theme to use

Usage
---------
```
ansible-playbook main.yml
```

Uninstall
---------
```
ansible-playbook main.yml --tags uninstall
```