# Security Policy

## Reporting a vulnerability

Please **do not** open a public GitHub issue for security reports.

Instead, use one of the following private disclosure paths:

- **Preferred:** GitHub Security Advisories for this repository ("Report a vulnerability")
- If you cannot use advisories, open a draft pull request with minimal details and ask maintainers to move the discussion to a private channel

When reporting, include:

- A description of the issue and potential impact
- Steps to reproduce (proof-of-concept if available)
- Affected configuration (nested/winit vs TTY/DRM, distro, kernel)
- Logs/backtraces if relevant (`RUST_LOG=debug`, `RUST_BACKTRACE=1`)

## Supported versions

This project is under active development. Security fixes, when available, are generally applied to:

- The `main` branch
- The most recent tagged release (if/when releases are published)

## Response expectations

We’ll try to acknowledge receipt within a few days and will coordinate a fix and disclosure timeline with you when appropriate.
