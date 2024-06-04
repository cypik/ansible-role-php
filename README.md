<p align="center"> <img src="https://user-images.githubusercontent.com/50652676/62451340-ba925480-b78b-11e9-99f0-13a8a9cc0afa.png" width="100" height="100"></p>

<h1 align="center">
    Ansible Role php
</h1>
An Ansible role to install and configure Metabase on a target system.

## Table of Contents
- [Role Variables](#Role Variables)
- [Example Playbook](#Example Playbook)
- [License](#license)

## Role Variables

- `nginx_php_listen_port`: Specify the php port to user.
- `php_versionr`: Specify the installation version php.

- [Add any other configurable variables]

## Dependencies

- [List any dependencies or other roles required by this role]

## Example Playbook

```yaml
- hosts: servers
  roles:
    - { role: ansible-role-php, php_version: "7.4" }

```
## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/cypik/ansible-role-php/blob/master/LICENSE) file for details.
