=======
Vector-role
=========

Installs Vector.

Requirements
------------

- Ansible 2.9 или выше

Role Variables
--------------

ansible_architecture: = "x86_64"

ansible_user_id: = "user"

ansible_user_gid: = "1001"

vector_url: "https://packages.timber.io/vector/0.33.1/vector-0.33.1-1.x86_64.rpm"

vector_config_path: "/etc/vector"

data_dir: "/var/lib/vector"

Dependencies
------------



Example Playbook
----------------

```
- hosts: vector
     roles:
      - role: vector-role
```

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
