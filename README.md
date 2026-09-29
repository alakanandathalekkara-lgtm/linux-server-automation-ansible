# Linux Server Automation using Ansible

## Project Overview

This project automates Linux server configuration and provisioning using Ansible.

The automation uses reusable Ansible roles, YAML playbooks, and Jinja2 templates to configure a Linux server consistently and repeatably.

## Technologies Used

- Ansible
- Rocky Linux
- YAML
- Jinja2
- Apache HTTP Server
- Firewalld
- SELinux
- SSH

## Project Architecture

- Ansible Control Node
- Linux Managed Node
- SSH key-based authentication

## Automation Tasks

- Install common Linux packages
- Create a DevOps user
- Install and configure Apache
- Deploy a dynamic webpage using Jinja2
- Start and enable Apache
- Configure Firewalld
- Allow HTTP and HTTPS
- Configure SELinux context
- Apply repeatable server configuration

## Project Structure

```text
linux-server-automation-ansible/
├── ansible.cfg
├── requirements.yml
├── .gitignore
├── README.md
├── inventory/
│   ├── hosts
│   └── hosts.example
├── playbooks/
│   └── site.yml
└── roles/
    ├── common/
    ├── users/
    ├── webserver/
    └── firewall/
