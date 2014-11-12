psacct - Process accounting
===========================

Ansible role to manage *psacct*.  More information about *psacct* is
available:

- http://linux.die.net/man/8/accton
- http://www.cyberciti.biz/tips/howto-log-user-activity-using-process-accounting.html

Requirements
------------

No external dependencies.

Role Variables
--------------

None.  Just import the role for process accounting.

Dependencies
------------

None.

Example Playbook
----------------

Example:

    - hosts: servers
      roles:
         - { role: sfromm.psacct }

License
-------

GPLv2

Author Information
------------------

See https://github.com/sfromm
