# DEPRECATION WARNING
This Ansible role has been deprecated in favor of collection [`almaops.common`](https://github.com/almaops/ansible-collection-common/tree/master/roles/flush_handlers) which is advised to be used instead.

aboveops.flush_handlers
=========

Flush ansible handlers

Description
-----------

This role flushes ansible handlers. You can just insert it between other roles, no need to create separate ansible plays when you need it.


Example
-------

    - role: aboveops.flush_handlers

Install
-------

This role can be installed from [Ansible Galaxy](https://galaxy.ansible.com/):

`ansible-galaxy install aboveops.flush_handlers`

License
-------

MIT

Author Information
------------------

Dmitrii Kashin, <freehck@freehck.com>
