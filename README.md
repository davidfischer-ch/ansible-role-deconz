# Ansible Role deCONZ

Library of Ansible plugins and roles for deploying various services.
See [ansible-roles](https://github.com/davidfischer-ch/ansible-roles) for additional documentation.

This repository hosts the role deCONZ and may depend of other roles and plugins of the library.

## Dependencies

See [meta](meta/main.yml).

## Variables

TODO VARIABLES

## Example

Example for installing deCONZ on a host.

### Playbook

```
---

- hosts:
    - domotic
  roles:
    - deconz
  vars:
    deconz_role_action: setup

    # UFW

    ssh_port: '{{ ansible_port }}'

    # Domotic

    deconz_instance_name: deconz
```

## License

See [LICENSE.rst](LICENSE.rst).

## Authors

See [AUTHORS](AUTHORS).

2014-2022 - David Fischer
