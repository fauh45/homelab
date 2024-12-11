# Ansible Deployment Automation

Deployment scripts written using ansible to deploy/configure applications.

## Playbook

All the playbook related to the homelab is saved on `./playbooks/`.

### allow-remote-access.yaml

> [!WARNING]
> Requires root, also please run this first before any of the playbook after this

Allows all ports for remote access to be used. Currently it's only SSH.

### deploy-home-assistant.yaml

> [!WARNING]
> Requires root

Deploys Home Assistant Core with HA user `homeassistant`.

### upsert-dns-server.yaml

> [!WARNING]
> Requires root

This playbook is used to either install or upgrade the Technitium DNS server deployed to `thin0`.
