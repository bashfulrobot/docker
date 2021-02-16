Role Name
=========

This role will insall Docker on Ubuntu.

Requirements
------------

It is recommended to install:

``` shell
sudo apt install aptitude ansible apt-transport-https git -y
```

Role Variables
--------------

User and home are populated by using `{{ lookup('env','USER') }}` in the role. No need for other variables.

Dependencies
------------

No dependencies on other roles.

License
-------

MIT

Author Information
------------------

Dustin Krysak
