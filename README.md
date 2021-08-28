# jtprogru.logrotate

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-logrotate/CI?label=CI)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-logrotate/Release?label=Release)
![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-logrotate)
[![Ansible Role](https://img.shields.io/ansible/role/54364)](https://galaxy.ansible.com/jtprogru/logrotate/)
[![GitHub tag](https://img.shields.io/github/tag/jtprogru/ansible-role-logrotate.svg)](https://github.com/jtprogru/ansible-role-logrotate/tags)

Simple role for manage `logrotate` configuration.


## Role Variables


See [`defaults/main.yml`](defaults/main.yml).


## Example Playbook

Example playbook:
```yaml
---
- name: Manage logrotate
  hosts: all
  become: true

  roles:
    - jtprogru.logrotate
```

## Author

Michael Savin aka `@jtprogru`

Twitter: [![Twitter Follow](https://img.shields.io/twitter/follow/jtprogru?color=gree&style=plastic)](https://twitter.com/jtprogru/)

## License

See [LICENSE](LICENSE.md)
