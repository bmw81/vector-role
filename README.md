vector-role
=========

Role for install and settings Vector service

Requirements
------------

Ansible >= 2.7 (It might work on previous versions, but we cannot guarantee it)

Role Variables
--------------

Name | Default Value | Descripton
:--- |:-----:| -------:
ansible_user_id | mike		 |	Ansible User ID
ansible_user_gid |	mike		 |	Group ID of Ansible User

Dependencies
------------

- Clickhouse

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: vector-vm
      roles:
        - vector-role

License
-------

BSD

Author Information
------------------

Mike White
