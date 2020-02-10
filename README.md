Ansible role for texinfo
==================================

Installs texinfo from source

[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-texinfo/workflows/Molecule%20Test/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-texinfo/actions?query=workflow%3A%22Molecule+Test%22)
[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-texinfo/workflows/Release/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-texinfo/actions?query=workflow%3A%22Release%22)

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

License
-------

[Apache License](LICENSE)
