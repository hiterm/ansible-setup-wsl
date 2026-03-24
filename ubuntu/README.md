# ansible-setup-ubuntu-wsl (WIP)

## setup

```
sudo apt update
sudo apt install ansible
```

## dry run

```
ansible-playbook --ask-become-pass --check -v playbook.yaml
```

## run

```
ansible-playbook --ask-become-pass playbook.yaml
```
