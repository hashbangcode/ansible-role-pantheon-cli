# Ansible Role: Pantheon CLI

[![Build Status](https://travis-ci.org/hashbangcode/ansible-role-pantheon-cli.svg?branch=master)](https://travis-ci.org/hashbangcode/ansible-role-pantheon-cli)

An Ansible role that installs the [Pantheon CLI](https://github.com/pantheon-systems/terminus) (aka Terminus).


## Requirements

Terminus requires PHP and cURL to be installed and available on the command-line.

At the very least you need these packages installed:

- PHP version 5.5.9 or later
- PHP-CLI
- PHP-CURL


## Role Variables

- `pantheon_cli_version`: current default is `0.13.6`


## Dependencies

None.


## Example Playbook

```
- hosts: servers
  roles:
     - { role: hashbangcode.pantheon-cli }
```

## License

MIT


## Author Information

This role was created by [Dan Bohea](http://bohea.co.uk) originally for use with [Vlad](https://github.com/hashbangcode/vlad).
