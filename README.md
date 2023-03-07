# ansible-system_bashrc

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_bashrc-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_bashrc)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_bashrc.svg)](https://github.com/lotusnoir/ansible-system_bashrc/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_bashrc?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_bashrc)
[![downloads](https://img.shields.io/ansible/role/d/56927)](https://galaxy.ansible.com/lotusnoir/system_bashrc)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56927)](https://galaxy.ansible.com/lotusnoir/system_bashrc)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Configure system bashrc

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

With default variables, this role assume it doesnt change anything on the system. You need to set the config variables like in the exemple in order to start configuration.

## Examples

        ---
        - hosts: system_bashrc
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_bashrc
          vars:
            bashrc_users_configure:
              - root
            bashrc_users_file:
              root: "/root/.bashrc"



## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
