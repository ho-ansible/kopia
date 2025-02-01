# Ansible role: kopia
Backup client for Linux

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `kopia_config`: contents of `repository.config`

## Playbooks
+ `main.yml`: apply role
+ `uninstall.yml`: remove. Run prior to removing host from inventory group.

## Dependencies
None.

## License
+ Ansible role licensed [MIT](LICENSE)

## Author Information
+ [Kopia](https://kopia.io/)
+ Ansible role by [Sean Ho](https://github.com/ho-ansible/)
