# Ansible Role: Install ruby-install
[![Build Status](https://travis-ci.org/ferrarimarco/ansible-role-ruby-install.svg?branch=master)](https://travis-ci.org/ferrarimarco/ansible-role-ruby-install)

An Ansible role that installs ruby-install.

## Using the role
### Installation
```
ansible-galaxy install ferrarimarco.ruby-install
```

### Variables
```
ruby_install_version: 0.6.0
```

### Example Playbook
```
  - hosts: all
    roles:
      - ferrarimarco.ruby-install
```
