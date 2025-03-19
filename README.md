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

## License

MIT

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/my-new-feature`)
5. Create a new Pull Request

## Author Information

Lucas Janin
- Mastodon: [https://mastodon.social/@lucas3d](https://mastodon.social/@lucas3d)
- Website: [https://www.lucasjanin.com](https://www.lucasjanin.com)
- GitHub: [github.com/lucasjanin](https://github.com/lucasjanin)
- LinkedIn: [linkedin.com/in/lucasjanin](https://linkedin.com/in/lucasjanin)