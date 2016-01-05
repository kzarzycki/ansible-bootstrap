Role Name
=========

Bootstrap ansible node. Assumes only root access is possible. Execute playbook with `ansible-playbook bootstrap.yml -u root --private-key root_access_key`

Requirements
------------

Private key installed on the machine

Example Playbook
----------------
- hosts: all
  user: root
  become: False
  roles:
    - bootstrap 

License
-------

BSD

Author Information
------------------
Krzysztof Zarzycki
