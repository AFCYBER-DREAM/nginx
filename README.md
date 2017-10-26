NGINX
=====

The purpose of this role is to install and configure nginx.

Requirements
------------

Ensure that an up to date version of this role is available.

Role Variables
--------------

The default variables are stored in **defaults/main.yml** and are:

* packages_to_install:
* enabled_services:

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Set up NGINX
      hosts: all
      become: True
      gather_facts: true

      roles:
        - nginx

License
-------

MIT

Author Information
------------------

The Development Range Engineering, Architecture, and Modernization (DREAM) Team.
