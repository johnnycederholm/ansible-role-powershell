Drawio
=========

Downloads the latest Powershell release from Github and installs it.

Dependencies
------------
community.general collection - install with `ansible-galaxy collection install community.general`
github3.py

Example Playbook
----------------

    - hosts: desktop
      roles:
         - powershell

License
-------

MIT