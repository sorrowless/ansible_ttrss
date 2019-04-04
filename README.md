sbog/ttrss
==========

Role to install and configure ttrss.

#### Requirements

Ansible 2.4

#### Role Variables

Look for these at `defaults/main.yml` file.

#### Dependencies

None

#### Example Playbook

```yaml
- name: Install and configure ttrss
  hosts: ttrss
  remote_user: root
  roles:
    - ttrss
```

#### License

Apache 2.0

#### Author Information

Stanislaw Bogatkin (https://sbog.ru)
