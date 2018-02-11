# wilmardo.matchbox

[![Build Status](https://travis-ci.org/wilmardo/ansible-role-matchbox.svg?branch=master)](https://travis-ci.org/wilmardo/ansible-role-matchbox)
[![Galaxy](https://img.shields.io/badge/galaxy-wilmardo.matchbox-blue.svg)](https://galaxy.ansible.com/wilmardo/matchbox/)

This role installs the CoreOS Matchbox to provision Container Linux clusters

## Requirements

None.

## Role Variables

### Default usage

As default Domoticz is installed and running http on port 8080 and https on port 8081 with the default certificate. 
If you want to adapt this to your needs look at the [Advanced usage](#advanced-usage) section.

### Advanced usage
```yaml
```

## Dependencies

None

## Example Playbook

Install Matchbox with the default settings
```yaml
- hosts: matchbox
  roles:
     - { role: wilmardo.matchbox }
```
After running the playbook Matchbox can be found at 0.0.0.0:8080 and gRPC at 0.0.0.0:8081

## License

BSD-3-Clause-Clear

## Author Information

This role was created in 2018 by [Wilmar den Ouden](https://wilmardenouden.nl).
