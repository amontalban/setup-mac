# setup-mac

This repository contains the apps I install on my systems.

## Requirements

- Up to date macOS
- [XCode](https://developer.apple.com/xcode/) installed
- [Brew](https://brew.sh)
- Ansible (`brew install ansible`)

Then run:

```
ansible-galaxy collection install -r requirements.yaml
ansible-playbook macos.yaml
```