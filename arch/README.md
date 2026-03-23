# ansible-setup-arch-wsl (Arch WSL)

## setup

```
sudo pacman -S ansible
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
