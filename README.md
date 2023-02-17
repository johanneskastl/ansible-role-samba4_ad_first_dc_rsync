![Ansible Lint](https://github.com/johanneskastl/ansible-role-samba4_ad_first_dc_rsync/workflows/Ansible%20Lint/badge.svg)

samba4_ad_first_dc_rsync
=========

Setup the rsync service on the first DC of a Samba4 AD

Requirements
------------

None.

Role Variables
--------------

- `xinetd_packages`: list of packages to be installed
- `path_to_sysvol`: path to the Samba4 AD sysvol directory
- `sysvol_replication_user`: name of the replication user
- `sysvol_replication_password`: password of the replication user

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: 'johanneskastl.samba4_ad_first_dc_rsync'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
