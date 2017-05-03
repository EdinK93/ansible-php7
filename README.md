Ansible role for PHP7
=====================

[![Build
Status](https://travis-ci.org/pixelfusion/ansible-php7.svg?branch=master)](https://travis-ci.org/pixelfusion/ansible-php7)

Ansible role to install PHP7 on Debian based systems.

Role variables
--------------


Configuring virtual hosts
-------------------------

```
- hosts: web
  vars:
  roles:
    - pixelfusion.php7
```

License
-------

MIT

