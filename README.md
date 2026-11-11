# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md# Ansible Infrastructure Automation

Automating Linux server provisioning, configuration management, and web server deployment using Ansible.

## Project Overview

This project demonstrates infrastructure automation using Ansible to manage multiple Ubuntu servers from a centralized control node.

The environment consists of one Ansible Controller and two managed Ubuntu servers.

## Architecture

- Ansible Controller: Central automation node.
- Web1: First managed web server.
- Web2: Second managed web server.
- SSH: Secure communication between nodes.
- Nginx: Web server.
- Ansible Roles: Reusable automation components.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Ubuntu | 24.04 |
| Ansible | 2.18.5 |
| Python | 3.12.3 |
| Nginx | Web server |
| OpenSSH | Remote connectivity |
| YAML | Playbook configuration |
| Jinja2 | Dynamic templates |
| Git | Version control |

## Project Structure

```text
ansible-infrastructure-automation/
├── ansible.cfg
├── inventory/
│   ├── hosts.ini
│   ├── group_vars/
│   └── host_vars/
├── playbooks/
│   ├── system-audit.yml
│   ├── install-nginx.yml
│   ├── deploy-web.yml
│   ├── deploy-template.yml
│   ├── configure-nginx.yml
│   ├── manage-users.yml
│   ├── configure-sudo.yml
│   └── use-nginx-role.yml
├── roles/
│   └── nginx/
│       ├── defaults/
│       ├── handlers/
│       ├── tasks/
│       └── templates/
├── templates/
│   └── index.html.j2
├── docs/
│   └── architecture.md
├── .gitignore
└── README.md
