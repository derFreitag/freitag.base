freitag.base
============
Ansible role to install system wide utilities.

Requirements
------------
None

Role Variables
--------------
None

Dependencies
------------
Depends on ``geerlingguy.ntp``.

Example Playbook
----------------
    - hosts: servers
      roles:
         - { role: freitag.base  }

License
-------
GPLv3

Author Information
------------------
Gil Forcada Codinachs (der Freitag)
