# Ansible Role: Disable swap

[![Build Status](https://travis-ci.org/dsgnr/ansible-role-disable-swap.svg?branch=master)](https://travis-ci.org/dsgnr/ansible-role-disable-swap)

This role disables the swapfile on a device

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: all
      become: true
      
      roles:
        - disable-swap

## License

GNUv3

## Author Information

This role was created by [Dan Hand](https://danielhand.io).

