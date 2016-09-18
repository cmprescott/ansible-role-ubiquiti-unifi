Ansible Role: Ubiquiti Unifi
=========
[![Build Status](https://travis-ci.org/cmprescott/ansible-role-ubiquiti-unifi.svg?branch=master)](https://travis-ci.org/cmprescott/ansible-role-ubiquiti-unifi)

Installs Ubiquiti Unifi management webapp.

Requirements
------------

```shell
case $OSTYPE in
  # Linux needs apt
  "linux"*)
      apt --version;;
esac
```

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: servers
      roles:
         - name:
           role: cmprescott.ubiquiti-unifi
```

License
-------

BSD

Author Information
------------------

Prescott Chris