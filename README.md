ansible-role-systemd-networking
===============================

Set up a static IP and caching DNS resolver using systemd-networkd and systemd-resolved.

Requirements
------------



Role Variables
--------------

Each host should have an int_ip_addr variable that specifies the IP address. 

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-systemd-networking }

License
-------

MIT

Author Information
------------------

https://github.com/jabl
