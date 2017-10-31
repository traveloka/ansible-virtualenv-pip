# shared/virtualenv_pip #

Installs virtualenv from pip.

## Requirements ##

No special pre-requisites.

## Role Variables ##

None.

## Dependencies ##

    - role: shared/pip

## Example Playbook ##

    - hosts: servers
      roles:
        - role: shared/virtualenv_pip
          apt_cache_valid_time: 21600
