# Ansible Role: Pantheon CLI

An Ansible role that installs the [Pantheon CLI](https://github.com/pantheon-systems/cli) (aka Terminus) on Linux and OS X.


## Requirements

Terminus requires PHP and curl to be installed and available on the command-line.

At the very least you need these packages installed:

- PHP version 5.3.2 or later
- PHP-CLI
- PHP-CURL


## Role Variables

- `pantheon_cli_version`: current default is `0.10.0`


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
