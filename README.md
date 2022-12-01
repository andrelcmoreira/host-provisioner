# host-provisioner

[![ci](https://github.com/carvalhudo/host-provisioner/actions/workflows/ci.yml/badge.svg)](https://github.com/carvalhudo/host-provisioner/actions/workflows/ci.yml)

## Overview

The ```host-provisioner``` project conconsisoftsn ansible playbook targeted to automate the full configuration of my fresh linux-like distro installation. The deployied configuration is available at [configs](https://github.com/carvalhudo/configs) repo. The playbooks are responsible for:

- package installing
- dotfiles deployment
- graphics configuration
- general user configuration

## Running the playbook

```bash
$ ansible-playbook -i <path_to_hosts_file> provision_host.yml -K
```

## Supported hosts

- void linux
