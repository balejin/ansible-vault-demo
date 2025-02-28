# Ansible Vault Demo

# Overview

This repository demonstrates how to use Ansible Vault to manage sensitive data like passwords, API keys, and other secrets securely within Ansible playbooks. It includes step-by-step instructions on encrypting, storing, and using secrets in a structured project.

# Features

Encrypt and store sensitive variables securely.

Reference encrypted values in Ansible playbooks.

Execute playbooks with vault-protected secrets.

Manage multiple vault passwords for different environments.

# Usage

Run the playbook with a vault password prompt:

ansible-playbook -i inventory.ini playbook.yml --ask-vault-pass

For detailed setup and operations, refer to the provided documentation.
