# ansible-setup-arch-wsl (Fedora WSL)

## setup

```
sudo dnf install ansible
ansible-galaxy collection install -r requirements.yml
```

## dry run

```
ansible-playbook --ask-become-pass --check -v playbook.yaml
```

## run

```
ansible-playbook --ask-become-pass playbook.yaml
```