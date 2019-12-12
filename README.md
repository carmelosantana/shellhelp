# Shellper

> Simple tools to automate server provisioning and maintenance.

<p align="center">
<img src="https://github-shellhelp.s3.amazonaws.com/f5-lamp-640.gif" />
</p>

## Compatible with

`Ubuntu 18.04 LTS`
 
## Usage

1. Automated install

```bash
curl -sSL https://github.com/carmelosantana/shellper/blob/master/install.sh | bash
```

## Contents

```bash
Joblets:
  - install_lamp

Functions:
  - apache_restart
  - apt_update_upgrade
  - ask_mariadb_mysql
  - ask_new_sudo_user
  - ask_security
  - crontab_backup
  - current_ssh_users
  - echo_install_complete
  - file_change_append
  - get_parent_dir
  - get_all_users
  - get_lamp_status
  - hdd_test
  - increase_lvm_size
  - install_apache_mod_security
  - install_chrome
  - install_fish
  - install_geekbench
  - install_lamp
  - install_mariadb
  - install_maxmind
  - install_memcached
  - install_mycroft
  - install_mysql
  - install_ondrej_apache
  - install_ondrej_php
  - install_php_test
  - install_postfix
  - install_security
  - install_speedtest
  - install_syncthing
  - install_terminal_utils
  - install_webmin
  - set_debian_frontend_noninteractive
  - setup_apache
  - setup_mysql
  - setup_security
  - setup_sudo_user
  - setup_permit_root_login
  - setup_unattended_upgrades
```

## ToDo

- [ ] Installer /usr/bin
- [ ] Apache Superset installer
- [ ] WordPress joblets
- [ ] *Secure* LAMP

## License

[MIT](https://en.wikipedia.org/wiki/MIT_License)
