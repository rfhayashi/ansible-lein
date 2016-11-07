Role Name
=========

Ansible role that installs Leiningen.

Requirements
------------

A JDK must be pre-installed. This role only installs Leiningen.

Role Variables
--------------

    lein_version: 2.7.1

Dependencies
------------

None.

Example Playbook
----------------

- hosts: servers
      roles:
         - { role: rfhayashi.lein }

License
-------

MIT