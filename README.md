[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/aws_s3_get/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/aws_s3_get/tree/main)

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
