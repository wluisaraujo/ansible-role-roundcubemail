[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-RoundCube%20WebMail-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-roundcubemail) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-roundcubemail.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-roundcubemail)
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
    - roundcubemail
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
