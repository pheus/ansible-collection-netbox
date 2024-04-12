# Ansible Role: NetBox Install

Installs and configures [NetBox](https://github.com/netbox-community/netbox) as recommended in the [installation guide](https://docs.netbox.dev/en/stable/).

## Requirements

The role requires the following Ansible collections to be available:

  - community.django
  - community.postgres

Additionally NetBox has some requirements for the targeting host:

  - Operating Systems:
    - 20.04 (focal)
    - 22.04 (jammy)
  - Python Versions:
    - 3.8 or higher
  - PostgreSQL database server:
    - 12 or higher
  - Redis caching server:
    - 4.0 or higher


## Role Variables

TBD

## Dependencies

No dependencies on other (standalone) roles.

## Example Playbook

This role can be used with a simple playbook:

```yaml
- name: Install and configure NetBox
  hosts: netbox_server

  tasks:
    - name: Import install role from NetBox collection
      import_role:
        name: pheus.netbox.nb_install
```

## License

GNU General Public License v3.0 or later.

See [LICENSE](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.

## Author Information

This Ansible role was created in 2024 by Martin Hauser
