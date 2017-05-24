# Ansible role for Black Goat on RHEL/CentOS 7

Deploys the [MBL course and investigator data platform](https://github.com/erickpeirson/mbl-browser) on a RHEL/CentOS 7 server via Gunicorn behind NginX.

## Requires

- [ansible-nginx-role](https://github.com/diging/ansible-nginx-role)
- [ansible-postgresql-role](https://github.com/diging/ansible-postgresql-role)
- [ansible-python-role](https://github.com/diging/ansible-python-role)
- [ansible-supervisor-role](https://github.com/diging/ansible-supervisor-role)
- [ansible-redis-role](https://github.com/diging/ansible-redis-role)
