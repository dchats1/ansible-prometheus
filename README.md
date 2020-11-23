Role Name
=========

Deploy Prometheus in a podman container either as a single instance or as a HA Pair.

Requirements
------------

This requires the containers.podman collection: https://galaxy.ansible.com/containers/podman

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

No Dependencies at this time

Example Playbook
----------------

    - hosts: podman_host
      roles:
         - prometheus

License
-------

BSD

Author Information
------------------

David Chatterton
david@davidchatterton.com
