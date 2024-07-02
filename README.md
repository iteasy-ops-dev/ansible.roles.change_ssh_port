Ansible Role: Change SSH Port
=========

ssh 포트를 변경합니다.

Requirements
------------
None.

Role Variables
--------------
- `defaults/main.yml` 참조
```yaml
new_port: "22"
```

Dependencies
------------
None.

Example Playbook
----------------
- `test/` 참조
```yaml
- hosts: vms
  remote_user: root
  roles:
    - ansible.roles.change_ssh_port
```

License
------------
BSD

