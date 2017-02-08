Apt Cacher NG
=============

This role is designed to install apt-cacher-ng for apt packages caching.

Requirements
------------

None

Role Variables
--------------

* apt_cacher_ng_user: apt-cacher-ng
* apt_cacher_ng_group: apt-cacher-ng
* apt_cacher_ng_service_name: apt-cacher-ng
* apt_cacher_ng_container_prefix: shelleg/apt-cacher-ng
* apt_cacher_ng_container_name: "{{ apt_cacher_ng_container_prefix }}:{{ apt_cacher_ng_container_version }}"
* apt_cacher_ng_container_port: 3142
* apt_cacher_ng_dir: /etc/apt
* apt_cacher_ng_client_file: /etc/apt/apt.conf.d/01proxy

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: apt-cacher-ng

License
-------

Apache

Author Information
------------------

[Tikal DevOps Team](http://www.tikalk.com/devops/)
