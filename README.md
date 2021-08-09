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


Example Playbook
----------------


    - hosts: servers
      roles:
         - jusanherndon.user_config 

License
-------

BSD

Author Information
------------------

