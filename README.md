spk83.provision-thinpool
=========================

Creates a logical value configured as thinpool to use devicemapper in direct-lvm mode as storage driver primarily for docker

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - spk83.provision-thinpool
```

License
-------

MIT

Author Information
------------------

Vishal Shah vishal.shah@nyu.edu
