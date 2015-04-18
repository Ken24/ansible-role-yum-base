Ansible Role: YUM (Development Tools )
======================================

* Update packages.
* Install basic packages (ex: screen and libselinx-python).
* Add ``.screenrc``

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: Ken24.yum-base }

License
-------

MIT

Author Information
------------------

This role was created by Kenta Nishimura
