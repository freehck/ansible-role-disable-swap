freehck.disable_swap
=========

Disable swapping in your system

Description
-----------

This role disable active swaps and remove them from fstab

Example
-------

    - hosts: all
      become: true
      roles:
        - role: freehck.disable_swap

Install
-------

This role can be installed from [Ansible Galaxy](https://galaxy.ansible.com/):

`ansible-galaxy install freehck.disable_swap`

License
-------

MIT

Author Information
------------------

Dmitrii Kashin, <freehck@freehck.ru>
