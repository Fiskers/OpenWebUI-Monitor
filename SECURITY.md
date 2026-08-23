# Security Policy

## Supported code

Security reports should target the latest commit on the default branch. This fork may differ from the upstream project, so include the affected repository URL and commit SHA.

## Reporting a vulnerability

Do not disclose suspected vulnerabilities in public issues, discussions, pull requests, logs, screenshots, or commits.

Report vulnerabilities privately through:

https://github.com/Fiskers/OpenWebUI-Monitor/security/advisories/new

If the same issue affects the unmodified upstream project, also follow the upstream maintainers' private reporting process.

Include reproduction steps, affected routes or versions, expected and observed behavior, impact, and a minimal proof of concept. Remove or replace all real credentials and personal data.

## Sensitive configuration

Treat these values as secrets:

- `OPENWEBUI_API_KEY`
- `API_KEY`
- `ACCESS_TOKEN`
- database passwords and connection strings

Never commit them to the repository, include them in URLs, or expose them in client-side code, screenshots, build logs, or error messages. Revoke and replace any credential that may have been exposed.

## Priority areas

Reports involving authentication bypass, unauthorized database initialization, user or usage-data exposure, balance manipulation, injection, server-side request forgery, or credential leakage are especially important.
