# shared/virtualenv_pip #

Installs virtualenv from pip.

## Requirements ##

No special pre-requisites.

## Role Variables ##

See default variables on defaults/main.yml

Optional Varibles:
- name: virtualenv_pip_version
  description: version of virtualenv to be installed if `virtualenv_pip_state` is set to present

## Dependencies ##

    - role: shared/pip

## Example Playbook ##

    - hosts: servers
      roles:
        - role: shared/virtualenv_pip

