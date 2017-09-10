docker ansible role
=========

It's just "bundle" of roles (check dependencies) required for any docker host.

Dependencies
------------

- AdnanHodzic.python-ubuntu-bootstrap
- dev-sec.os-hardening
- dev-sec.ssh-hardening
- tersmitten.fail2ban
- angstwad.docker_ubuntu

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: all
  gather_facts: False
  vars:
    ansible_ssh_transfer_method: scp #sftp will be disabled after fist run
  roles:
    - rakshazi.docker
```

License
-------

BSD
