# Ansible role: Kodi

Ansible role for installing Kodi media server on Ubuntu 18.04, 20.04, 22.04

## Requirements

None.

## Dependencies

None.

## Example playbook

    - hosts: all
      roles:
        - role: dragomirr.kodi

## Testing

Testing is done using [molecule](https://molecule.readthedocs.io/) with [vagrant](https://www.vagrantup.com/) and [virtualbox](https://www.virtualbox.org/).

Testing dependencies:

  - [vagrant](https://www.vagrantup.com/)
  - [virtualbox](https://www.virtualbox.org/)
  - molecule python package
  - molecule-vagrant python package

## Licence

GPLv3
