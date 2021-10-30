[![](https://github.com/ansible-roles-matsumura/aws_s3_get/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/aws_s3_get/actions?query=workflow%3Abuild)

Role Description
=========

Copy a file in the remote system to AWS S3.

Requirements
------------

boto and boto3 is installed in the remote system

Role Variables
--------------

See 'meta/argument_specs.yml'.

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - aws_s3_get
```

License
-------

BSD
