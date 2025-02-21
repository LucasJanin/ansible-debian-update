# Debian Update Ansible Playbook

## Description

Automated patching and updating playbook for Debian systems

## Prerequisites

- Ansible 2.9+
- Debian/Ubuntu systems
- Sudo access on target servers with ansible user

## Installation

1. Clone the repository
2. Configure `inventory/inventory.ini`
3. Adjust variables in `inventory/group_vars/`

## Usage

```bash
ansible-playbook -i inventory/inventory.ini playbooks/debian-update.yml
```

## Features

- Package updates
- Reboot management
- Update logging
- Old log cleanup

## Configuration

- Customize `inventory/group_vars/` to adjust group-specific parameters
- Modify log retention days (`log_keep_day`)

## Contributing

Pull requests are welcome.

## Author

Lucas Janin

- Mastodon: <https://mastodon.social/@lucas3d>
- Website: <https://www.lucasjanin.com>

## License

MIT License
