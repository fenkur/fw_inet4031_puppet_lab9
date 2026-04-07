# fw_inet4031_puppet_lab9

Lab 9/11 — Puppet automation scripts for configuring a LAMP stack server, managing users and groups, and verifying Puppet functionality on an Ubuntu system.

## Files

- `lamp_stack_server.pp` — Installs and configures Apache, MySQL, and PHP
- `phpinfo.php` — PHP info page to verify the web server setup
- `server_users_groups.pp` — Manages server users and group assignments
- `testing_puppet.pp` — Basic Puppet manifest to test agent/master communication

## Usage
```bash
# Apply a manifest with Puppet
sudo puppet apply lamp_stack_server.pp
```

## Requirements

- Ubuntu 24.04
- Puppet installed
- Root/sudo access

## Course

INET 4031 — System Administration
