# Ansible Role for PostgreSQL

[![Travis](https://img.shields.io/travis/com/alvistack/ansible-role-postgres.svg)](https://travis-ci.com/alvistack/ansible-role-postgres)
[![GitHub release](https://img.shields.io/github/release/alvistack/ansible-role-postgres.svg)](https://github.com/alvistack/ansible-role-postgres)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-postgres.svg)](https://github.com/alvistack/ansible-role-postgres/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.postgres-blue.svg)](https://galaxy.ansible.com/alvistack/postgres)

Ansible Role for PostgreSQL Installation.

## Requirements

This role require Ansible 2.9 or higher.

This role was designed for:

  - Ubuntu 18.04/19.10/20.04
  - RHEL/CentOS 7/8
  - openSUSE Leap 15.1
  - Debian 10
  - Fedora 32

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

[ansible-role-requirements.yml](ansible-role-requirements.yml)

## Example Playbook

[molecule/default/converge.yml](molecule/default/converge.yml)

This role could simply deploy to `localhost` as below:

    molecule converge -s default

## License

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

## Author Information

  - Wong Hoi Sing Edison
      - <https://twitter.com/hswong3i>
      - <https://github.com/hswong3i>
