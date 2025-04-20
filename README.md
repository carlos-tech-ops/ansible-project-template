# Ansible Project Template

![Status](https://img.shields.io/badge/project-template-active-blue)
![Tech Stack](https://img.shields.io/badge/built_with-Ansible-critical)

## Overview

This is my modular **Ansible Automation Project Template**, built for rapid deployment, repeatability, and clean structure in production-like environments. It follows Ansible best practices, GitOps-ready principles, and is tailored for use in cloud automation, Linux hardening, user provisioning, service management, and CI/CD integrations.

This repository is not just a folder layout — it’s a **battle-tested framework** I use in real automation labs and will scale with future roles, playbooks, and Ansible Galaxy roles.

## Features

- Modular `roles/` structure
- Dedicated inventory and configuration files
- Click-by-click GitHub creation (no CLI dependency)
- Beginner to advanced project-ready
- Easily extendable for:
  - Cloud provisioning (AWS, Azure)
  - Linux user management
  - Service control
  - Cron jobs and task scheduling
  - Security compliance automation

## Directory Structure

```bash
ansible-project-template/
├── ansible.cfg               # Ansible configuration
├── inventories/
│   └── hosts.ini             # Inventory file
├── playbooks/
│   └── main.yml              # Main playbook (calls roles)
├── roles/
│   └── sample_role/
│       ├── tasks/main.yml    # Task definitions
│       ├── vars/main.yml     # Variables (optional)
│       └── handlers/main.yml # Handlers (optional)
├── .gitignore
└── README.md
