Role Name
=========

This role can be used to install rabbitmq server on Ubuntu, Debian and RedHat servers.

Requirements
------------

No special requirements for this role to run.

Role Variables
--------------

* RABBITMQ_VERSION: specifies the required version to install (default is 3.6.14)

Dependencies
------------

No dependencies on other galaxy roles.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: mohsensy.rabbitmq, RABBITMQ_VERSION: 3.4.16 }

License
-------

BSD

Author Information
------------------

If you have any question please contact me on

[twitter](https://twitter.com/mouhsen_ibrahim)

[linkedin](https://linkedin.com/in/mohsen-ibrahim-670b13112/)

email mohsen47@hotmail.co.uk
