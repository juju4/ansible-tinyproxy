[![Actions Status - Main](https://github.com/juju4/ansible-tinyproxy/workflows/AnsibleCI/badge.svg)](https://github.com/juju4/ansible-tinyproxy/actions?query=branch%3Amain)
[![Actions Status - Devel](https://github.com/juju4/ansible-tinyproxy/workflows/AnsibleCI/badge.svg?branch=devel)](https://github.com/juju4/ansible-tinyproxy/actions?query=branch%3Adevel)

# tinyproxy ansible role

Setup [tinyproxy](https://tinyproxy.github.io/) - [source](https://github.com/tinyproxy/tinyproxy)

## Requirements & Dependencies

### Ansible
It was tested on the following versions:
 * 2.10

### Operating systems

Tested on Ubuntu 18.04, 20.04, Centos 7 and 8.

## Example Playbook

Just include this role in your list.
For example

```
- host: myhost
  roles:
    - juju4.tinyproxy
```

## Continuous integration

```
$ pip install molecule docker
$ molecule test
$ MOLECULE_DISTRO=ubuntu:20.04 molecule test --destroy=never
```

## Troubleshooting & Known issues

N/A

## License

BSD 2-clause
