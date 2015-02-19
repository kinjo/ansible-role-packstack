ansible-role-packstack
=========

Install OpenStack by Packstack

Requirements
------------

Tested on CentOS 6.5

Role Variables
--------------

See the [default variables](defaults/main.yml)

Example Playbook
----------------

    - hosts: openstack
      roles:
         - role: packstack
      sudo: yes

License
-------

MIT

Author Information
------------------

[Takumi KINJO](http://github.com/kinjo/)
