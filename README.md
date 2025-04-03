gitconfig
=========

Provisioning git command line configuration to rockylinux

Requirements
------------

No pre-requiste required.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    - hosts: localhost
      vars:
        gituseremail: {{ lookup('env', 'GITHUB_EMAIL') }}
        gitusername: {{ lookup('env', 'GITHUB_USERNAME') }}
        gittoken: {{ lookup('env', 'GITHUB_PASSWORD') }}
      roles:
        - hemanth22.gitconfig

License
-------

GPL-3.0-only

Author Information
------------------

This role was created in 2024 by Hemanth BITRA.
Author Website: bitroid.in
