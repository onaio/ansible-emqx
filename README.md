onaio.emqx
=========

Use this role to install and configure [EQMX](https://www.emqx.io/docs/en/v5.0/).

Role Dependencies
-----------------

This role requires the [community.general.modprobe](https://docs.ansible.com/ansible/latest/collections/community/general/modprobe_module.html) module which is a part of [community.general](https://galaxy.ansible.com/community/general?extIdCarryOver=true&sc_cid=701f2000001OH7YAAW)

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.


Example Playbook[TODO]
----------------

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

Apache 2.0
