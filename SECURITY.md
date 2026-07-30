# Security Policy

## Reporting a security issue

Please do not post passwords, API keys, private customer information, signing material, or exploitable security details in a public issue.

For now, security reports should be sent privately to the repository owner. Include:

- The affected Street Kittys Studio version and internal revision
- The operating system and architecture
- Clear reproduction steps
- The expected and actual behavior
- Relevant screenshots or redacted logs
- Whether private data, installation integrity, updates, or code signing may be affected

## Supported versions

Street Kittys Studio is currently in private beta. Security fixes may require installing the newest approved beta revision. Older beta revisions may not remain supported.

## Sensitive information

Never commit or attach:

- API tokens, passwords, or recovery codes
- Private release-signing keys
- Unredacted customer, donor, employee, medical, or financial records
- Private email or calendar exports
- Production database backups
- Logs containing credentials or personal data

## Release security

Approved releases should include a SHA-256 checksum. Production update catalogs and packages should use verified signatures when the signing system is available. Private signing keys must be stored outside this repository with restricted access.
