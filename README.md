mamercad.nagiosxi-server
========================

Stands up a Nagios XI server on RHEL/CentOS

Warnings
--------

The role puts SELinux into permissive mode and disabled firewalld

Requirements
------------

None

Role Variables
--------------

See the example playbook below, as well as vars/main.yml

Dependencies
------------

None

Example Playbook
----------------

    - hosts:
        - nagiosxi
      roles:
        - mamercad.nagiosxi-server

License
-------

GPLv3

Author Information
------------------

Mark Mercado <mamercad@umflint.edu>
