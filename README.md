# Ansible Collection - NetBox

This repository contains the `pheus.netbox` Ansible Collection.

## Tested with Ansible

Tested with ansible-core >=2.14 releases.

## External requirements

Some modules and plugins require external libraries. Please check the requirements for each plugin or module you use in the documentation to find out which requirements are needed.

## Included content

Please check the included content on the [Ansible Galaxy page for this collection](https://galaxy.ansible.com/pheus/netbox).

## Using this collection

```bash
ansible-galaxy collection install pheus.netbox
```

You can also include it in a `requirements.yml` file and install it via `ansible-galaxy collection install -r requirements.yml` using the format:

```yaml
collections:
  - name: pheus.netbox
```

To upgrade the collection to the latest available version, run the following command:

```bash
ansible-galaxy collection install pheus.netbox --upgrade
```

You can also install a specific version of the collection, for example, if you need to downgrade when something is broken in the latest version (please report an issue in this repository). Use the following syntax where `X.Y.Z` can be any [available version](https://galaxy.ansible.com/pheus/netbox):

```bash
ansible-galaxy collection install pheus.netbox:==X.Y.Z
```

See [Ansible Using collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html) for more details.

## Release notes

See the [changelog](https://github.com/pheus/ansible-collection-netbox/tree/main/CHANGELOG.rst).

## Licensing

GNU General Public License v3.0 or later.

See [LICENSE](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.
