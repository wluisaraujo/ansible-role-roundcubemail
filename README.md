[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-roundcubemail.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-roundcubemail)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Roundcube](https://roundcube.net/)
------------

Description
------------

 * Ansible for Roundcube WebMail

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-roundcubemail
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
