Ansible Common
==============

Install and configure the common packages on Debian server.

Installation
------------

git submodule add git@github.com/boostmyshoporganization/ansible-common roles/common

```yaml
roles:
    - common
```

Configuration
-------------

```yaml
common:
  environment: dev
  additional_packages:
    - vpnc
```