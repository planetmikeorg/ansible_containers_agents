Container Agents
=========

Deploy container based management agents to a host.

Requirements
------------

Podman mst be configured ahead of time.

Role Variables
--------------

See defaults/main.yml for now.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Monitoring Containers
      hosts: all
      become: true
      become_user: root
      roles:
        - planetmikeorg.containers_agents

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
