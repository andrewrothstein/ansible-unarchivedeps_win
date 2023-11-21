andrewrothstein.unarchivedeps_win
=========

![Build Status](https://github.com/andrewrothstein/ansible-unarchivedeps_win/actions/workflows/build.yml/badge.svg)

Installs the PowerShell modules necessary to support the ansible unarchive module on Windows

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
    - andrewrothstein.unarchivedeps_win
```

License
-------

MIT

Author Information
------------------

* Andrew Rothstein <andrew.rothstein@gmail.com>
* Victor Michel <victormichel95@gmail.com>
