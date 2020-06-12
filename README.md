# bootstrap-for-mac

This project is for automating my Mac setup.

## Requirement

- homebrew

## Preparation

1. Clone this project to the root of the user on the local machine.
2. Run `ln -s ~/bootstrap-for-mac/Brewfile ~/Brewfile`

## Brewfile

```bash
brew bundle
```

## Ansible

```bash
ansible-playbook playbooks/mac.yml -i inventory/default
```

