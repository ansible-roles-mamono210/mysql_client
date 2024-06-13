[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/mysql_client/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/mysql_client/tree/main)

Role Description
=========

Installs [MySQL Client](https://www.mysql.com) for Linux.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - mysql_client
```

License
-------

BSD
