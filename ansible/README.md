# Ansible Deployment Automation

Deployment scripts written using ansible to deploy/configure applications.

## Playbook

All the playbook related to the homelab is saved on `./playbooks/`.

### upsert-dns-server.yaml

> [!WARNING]
> Requires Root

This playbook is used to either install or upgrade the Technitium DNS server deployed to `thin0`.
