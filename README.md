# Potos - Specification for Potos Vanilla

This repository contains the specification for Potos Vanilla and can be used as a template for your own custom Linux Client based on Potos.

[![Test](https://github.com/projectpotos/ansible-specs-potos/actions/workflows/test.yml/badge.svg)](https://github.com/projectpotos/ansible-specs-potos/actions/workflows/test.yml)

## Most important files

### `files/templates/requirements.yml.j2`
A dynamic ansible galaxy requirements files for roles to be executed in that run. Have a look [here](https://github.com/projectpotos/ansible-specs-potos/blob/main/files/templates/requirements.yml.j2) for an example

### `templates/collections.yml.j2`
List with required collections that need to be installed e.g.
```
---
collections:
  - ansible.posix 
```
or [here](https://github.com/projectpotos/ansible-specs-potos/blob/main/templates/collections.yml.j2) the example from this repo

## 

# vars

# Templates

Get applied by the templating engine before the playbook run

# Files

Get copied to the playbook directory to be then later used in different roles
