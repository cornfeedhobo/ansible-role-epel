# ansible-role-epel [![Ansible Role](https://img.shields.io/ansible/role/d/cornfeedhobo/epel)](https://galaxy.ansible.com/cornfeedhobo/epel)

Install the EPEL repository. Useful as a dependency for other roles.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [epel_key_url](#epel_key_url)
  - [epel_package_name](#epel_package_name)
  - [epel_package_state](#epel_package_state)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.9`

## Default Variables

### epel_key_url

#### Default value

```YAML
epel_key_url: https://dl.fedoraproject.org/pub/epel/RPM-GPG-KEY-EPEL-{{ ansible_distribution_major_version
  }}
```

### epel_package_name

#### Default value

```YAML
epel_package_name: epel-release
```

### epel_package_state

#### Default value

```YAML
epel_package_state: present
```

## Discovered Tags

**_epel_**


## Dependencies

None.

## License

MIT

## Author

cornfeedhobo
