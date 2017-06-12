andrewrothstein.grabssh
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-grabssh.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-grabssh)

Utilities for working with ssh agents across broken connections. Inspired by [this](http://samrowe.com/wordpress/ssh-agent-and-gnu-screen/)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.grabssh
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
