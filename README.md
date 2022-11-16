# host-provisioner

[![void](https://github.com/carvalhudo/host-provisioner/actions/workflows/void.yml/badge.svg)](https://github.com/carvalhudo/host-provisioner/actions/workflows/void.yml)

## Overview

The ```host-provisioner``` project contains a set of ansible playbooks targeted to automate the full configuration of my fresh linux-like distro installation. The deployied configuration is available at [configs](https://github.com/carvalhudo/configs) repo. The playbooks are responsible for:

- package installing
- dotfiles deployment
- graphics configuration
- general user configuration

## Running the playbooks

```bash
$ cd hosts/<distro> && ansible-playbook -i <path_to_hosts_file> provision_host.yml -K
```

## Supported hosts

- void linux
