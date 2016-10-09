Ansible role - Swapfile
=========

Add swap file to Linux installation. For the sake of simplicity the swap file is created on an existing file system instead of using a swap partition (recommended approach). Some file systems are less suitable for swap files (eg. Btrfs).

Requirements
------------

Sufficient disk space

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - thecodingrobto.swapfile

License
-------

BSD
