Role: common
========

This role sets common configurations for all instance types. (debian)

Requirements
------------

Nothing, it runs out of the box.

Role Variables
--------------

In the current version, you can specify the following variables:

| Name               | Default |                                                              |
|--------------------|---------|--------------------------------------------------------------|
| admin_users        |   ---   | List containing all usernames to be created on target hosts. |


Dependencies
------------

This package has no dependencies.

License
-------

MIT

Author Information
------------------

Created by Sam Morrison
https://www.twitter.com/samcns

Examples
--------

```yaml
---
- name: common role test
  hosts: all
  roles:
    - cns.common
```
