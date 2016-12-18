Ansible Role: rancher-server
=========

An Ansible Role that installs a rancher server via docker on Debian/Ubuntu

Requirements
------------

Ansible version >2.2.0

Role Variables
--------------

Compatible OS Version:
- `Ubuntu 14/16`

Variable defaults
```
rancher_server_ip: ""
rancher_server_port: ""
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:


    - hosts: rancher-server
      vars:
        - rancher_server_ip: "127.0.0.1"
        - rancher_server_port: "8080"
      roles:
        - docker
        - rancher

License
-------

BSD

Author Information
------------------

Kai Möller / cheGGo / @kaifuzius on Twitter
