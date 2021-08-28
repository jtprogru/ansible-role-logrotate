# jtprogru.logrotate

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-logrotate/CI?label=CI)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-logrotate/Release?label=Release)
![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-logrotate)
[![Ansible Role](https://img.shields.io/ansible/role/56069)](https://galaxy.ansible.com/jtprogru/logrotate/)
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

## Authors

- Michael Savin
  - :octocat: [@jtprogru](https://www.github.com/jtprogru)
  - :bird: [@jtprogru](https://www.twitter.com/jtprogru)
  - :moneybag: [savinmi.ru](https://savinmi.ru)

## License

See [LICENSE](LICENSE.md)
