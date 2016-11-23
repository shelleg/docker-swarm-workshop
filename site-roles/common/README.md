Shelleg Common
==============

This role is desinged to provide common tasks and set certain facts which will be used in a Shelleg designed project.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

`internet_available` - this fact will be set to true as long as there is a Ping to `8.8.8.8` upon success this var will be set to `true` (Thanks Salo Shpigelman)[https://github.com/Saloshp].
`docker_mode` - this fact will be set in order to determine if the host has docker executable installed - upon success this var will be set to `true`.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: shelleg.common

License
-------

Apache

Author Information
------------------

[Tikal DevOps Team](http://www.tikalk.com/devops/)
