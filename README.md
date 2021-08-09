user_config
=========

This role will modify or create new users

Requirements
------------


Role Variables
--------------

* user: name of a user
* user_root: name of the root user 
* shell: location of defualt shell
* groups: list of groups user can belong to
* password: password of user
* password_root: password of root user
* ssh_public_key: name of ssh key files 

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
