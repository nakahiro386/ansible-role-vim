Role Name
=========

nakahiro386.vim

Install vim from source.

Requirements
------------

* git
* make

Role Variables
--------------

see ./defaults/main.yml

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: nakahiro386.vim
      become: yes
```

License
-------

MIT

