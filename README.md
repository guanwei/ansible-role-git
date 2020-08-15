# Ansible Role: Git

Installs Git on Debian/Ubuntu or Windows/Windows Core.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
git_packages:
  - git
```

## Dependencies

None.

## Example Playbook

requirements.yml
```
- name: git
  src: <repo_url>
  version: <branch_name>
  scm: git
```

playbook.yml
```
- hosts: servers
  roles:
    - git
```
