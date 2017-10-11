Role Name
=========

Ansible role to install docker community edition

Requirements
------------

Only YUM flavored OS are currently supported

Role Variables
--------------

`docker_repos` A dictionary of repo data. The default will add the stable docker repo.

Dependencies
------------

None

Example Playbook
----------------
```yaml
---
- name: Install docker
  hosts: docker
  become: True
  roles:
    - { role: ansible-docker }
```

License
-------

GPLv3

Author Information
------------------

Brad Searle
