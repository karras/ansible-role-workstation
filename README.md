# Ansible Collection - karras.workstation

A collection of roles to manage Linux-based development workstations.

![GitHub](https://github.com/karras/ansible-collection-workstation/workflows/Test/badge.svg?branch=main)

## Compatibility

Currently only supports Arch Linux.

## Roles

The following roles are part of this collection:

| Role                                | Purpose                    | Dependencies |
| ----------------------------------- | -------------------------- | ------------ |
| [greetd](./roles/greetd)            | Login manager greetd setup | n/a          |
| [hardware](./roles/hardware)        | Hardware related settings  | n/a          |
| [os\_baseline](./roles/os_baseline) | OS baseline configuration  | n/a          |
| [users](./roles/users)              | User and group management  | n/a          |
| [wayfire](./roles/wayfire)          | Wayfire compositor setup   | n/a          |

Whenever possible only Ansible builtin modules are leveraged, which can lead to
some more complex tasks structures though.

## Usage

TODO

## License

See [LICENSE](./LICENSE)
