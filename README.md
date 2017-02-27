Role Name
=========

A simple role to download the goss binary to /usr/local/bin and verify the checksum for a given version

Requirements
------------

None

Role Variables
--------------

goss_version: Defaults to v0.2.6, which is latest at the time of writing. Any new versions need to be handjammed into vars/main.yml because of the manual checksum validation. Currently supports "v0.2.5" and "v0.2.6". 

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: sean-abbott.install-goss, goss_version: v0.2.5 }

License
-------

GPLv2

Author Information
------------------

Sean's a pretty great guy. I'm not sayin', I'm just sayin'.
