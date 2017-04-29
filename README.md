Ajenti
======

The admin panel your servers deserve.
The panel will be available on __HTTPS__ port __8000__. The default username is __root__, and the password is __admin__

Requirements
------------

This role requires a debian compliant system such as knoppix or ubuntu.

Role Variables
--------------

ajentiv.enabled: Install common Ajenti plugins if Ajenti is enabled

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-ajenti, ajentiv.enabled: true }

Tasks
-----

  - Install [Ajenti](http://ajenti.org/) admin panel
  - Install [Ajenti V](http://ajenti.org/) plugin suite (if enabled in vars)

License
-------

BSD
