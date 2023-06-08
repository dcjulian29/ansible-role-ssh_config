# Ansible Role: ssh_config

[![Lint](https://github.com/dcjulian29/ansible-role-ssh_config/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-ssh_config/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-ssh_config.svg)](https://github.com/dcjulian29/ansible-role-ssh_config/issues)

This an Ansible role to configure per-host ssh client configurations.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.ssh_config
  src: https://github.com/dcjulian29/ansible-role-ssh_config.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
