# Install 1Password

[![Lint Code
Base](https://github.com/agoloncser/ansible-role-onepassword/actions/workflows/linter.yml/badge.svg)](https://github.com/agoloncser/ansible-role-git/actions/workflows/linter.yml)
[![Molecule
testing](https://github.com/agoloncser/ansible-role-onepassword/actions/workflows/ci.yml/badge.svg)](https://github.com/agoloncser/ansible-role-git/actions/workflows/ci.yml)

Ansible role to install 1Password from the official
repository. Follows the official [install
instructions](https://support.1password.com/install-linux/).

## Requirements

The role must run with elevated permissions (probably root).

## Role variables

None required.

## Example Playbook

```yaml
  - hosts: localhost
    vars:
    roles:
       - agoloncser.onepassword
```

## License

BSD

## Author Information

[@agoloncser](https://github.com/agoloncser)
