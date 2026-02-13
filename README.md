# ansible-role-email-oauth2-proxy
Ansible role for deploying [email-oauth2-proxy](https://github.com/simonrob/email-oauth2-proxy)

Installs email-oauth2-proxy using pip and creates a systemd service to run it.

## Before you read any further

This role is currently limited to support only a single O365 account using
OAUTH2 authentication.

It can be extended to support multiple accounts and other email providers.

Please create pull requests to add such support and/or other modifications.

## Variables

See [defaults/main.yml](defaults/main.yml)
