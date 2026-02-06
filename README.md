vector-role
=========

Installs Vector

Requirements
------------

- Ansible 2.9 или выше

Role Variables
--------------

```
|---------------------------|------------------------------------|
|  ansible_architecture     | Arch of the system (x86_64")       |
|  ansible_user_id          | The name of the user (user)        |
|  ansible_user_gid         | User`s GUID (1001)                 |
|  vector_url               | URL with thi dist                  |
|  vector_config_path       | Path for the config (/etc/vector)  |
|  data_dir                 | Data dir (/var/lib/vector)         |
|---------------------------|------------------------------------|
```

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

Vladimir Inshakov