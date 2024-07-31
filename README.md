Role Name
=========

This is a role created for deploying a nfs server that stores iso files.

Requirements
------------

* Ansible
* Jinja2
* Iso file

Role Variables
--------------

### defaults/main.yml

* servers: Dictionary that contains information about servers, it should contain hostname and ilo_baseuri.
  * hostname: Hostname of the servers
  * ilo_baseuri: url/ip of the ilo.

### vars/main.yml

* nfs_server_daemon: Name of the nfs server daemon to start.

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: nfs_server

License
-------

BSD

Author Information
------------------

* Oviedo Matias
* Schinca Mauro
