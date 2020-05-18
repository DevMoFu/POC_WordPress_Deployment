# PoC WordPress Deployment

Using Docker Compose and Ansible to deploy a typical "client" setup for a friend.

## Why?
Conversation with a friend (a developer) made me think about how to better onboard their clients.

## How?
Use infrastructure as code (iac) and DevOps tooling to automate and simplify the process.

## Requirements
- WordPress(Apache) - CRM
- MySQL - Database
- sftp - File access
- (optional) adminer - 
- (optional) traefik - Reverse proxy

## ToDo
- [x] Create Docker Compose file
- [ ] Create Ansible playbook to configure MySQL as desired
- [ ] Deploy to a VPC
