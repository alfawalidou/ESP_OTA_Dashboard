# Security Policy

This project manages OTA firmware delivery, so deployment credentials and firmware integrity should be treated carefully.

## Sensitive data

Do not commit Wi-Fi passwords, API tokens, SSH keys, device credentials, private certificates, or production `.env` files.

## OTA safety

- Verify firmware artifacts before publishing them.
- Keep production and test firmware channels separate.
- Review device targeting before rollout.
- Prefer staged deployments for changes that affect boot or networking.
- Keep a known-good rollback image available.

## Reporting a vulnerability

Please avoid publishing secrets or exploit details in a public issue. Share enough information to reproduce the problem while redacting credentials and identifiers.