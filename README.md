# Ansible Collection - glillico.server_setup

This collection includes roles that will help with the initial setup and configuration of a Linux server.

The roles included in this collection are listed below.

  - [add_rm_pkgs](https://github.com/glillico/ansible-role-add_rm_pkgs)
  - [auto_pkg_updates](https://github.com/glillico/ansible-role-auto_pkg_updates)
  - [configure_firewall](https://github.com/glillico/ansible-role-configure_firewall)
  - [configure_ntp](https://github.com/glillico/ansible-role-configure_ntp)
  - [configure_sshd](https://github.com/glillico/ansible-role-configure_sshd)
  - [configure_sudo](https://github.com/glillico/ansible-role-configure_sudo)
  - [copy_etc_issue](https://github.com/glillico/ansible-role-copy_etc_issue)
  - [install_docker](https://github.com/glillico/ansible-role-install_docker)
  - [install_fail2ban](https://github.com/glillico/ansible-role-install_fail2ban)
  - [manage_selinux](https://github.com/glillico/ansible-role-manage_selinux)
  - [reboot_server](https://github.com/glillico/ansible-role-reboot_server)
  - [regenerate_ssh_host_keys](https://github.com/glillico/ansible-role-regenerate_ssh_host_keys)
  - [set_hostname](https://github.com/glillico/ansible-role-set_hostname)
  - [setup_ssh_keys](https://github.com/glillico/ansible-role-setup_ssh_keys)
  - [setup_users](https://github.com/glillico/ansible-role-setup_users)
  - [sync_sudo](https://github.com/glillico/ansible-role-sync_sudo)
  - [update_pkgs](https://github.com/glillico/ansible-role-update_pkgs)
  
# Installation

This collection can be installed using the ansible-galaxy command.

`ansible-galaxy collection install glillico.server_setup`

Or you can include this collection in your ansible playbook's requirements.yml file:

```
---
collections:
  - name: glillico.server_setup
```

## License

MIT

## Author Information

Created in 2022 by Graham Lillico.
