Ansible role for texinfo
==================================

Installs texinfo from source

[![CircleCI](https://img.shields.io/circleci/build/github/mongodb-ansible-roles/ansible-role-texinfo/master?style=flat-square)](https://circleci.com/gh/mongodb-ansible-roles/ansible-role-texinfo)

Requirements
------------

None

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-------:|:--------:|
| `texinfo_package_url` | URL of textinfo package | string | http://ftp.gnu.org/gnu/texinfo/texinfo-6.7.tar.gz | no |
| `texinfo_version` | Version of texinfo to download | string | 6.7 | no |

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: ansible-role-texinfo
```

Development
-----------

Testing this role locally requires the CircleCI [Local CLI](https://circleci.com/docs/2.0/local-cli/).

To install the CLI for macOS and Linux, invoke the following command:

    $ curl -fLSs https://circle.ci/cli | DESTDIR=/usr/local/bin bash

After installing the CLI, invoke the following command to run the Molecule tests:

    $ make test

License
-------

[Apache License](LICENSE)
