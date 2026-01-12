# Security Policy

## Supported Versions

This action automatically tracks and builds the latest stable release from [felt/tippecanoe](https://github.com/felt/tippecanoe). Only the latest version is actively supported.

| Version | Supported          |
| ------- | ------------------ |
| latest  | :white_check_mark: |
| older   | :x:                |

## Reporting a Vulnerability

If you discover a security vulnerability in this GitHub Action, please report it by:

1. **For issues specific to this action** (build process, distribution): Open a private security advisory at [GitHub Security Advisories](https://github.com/MichaelKreil/tippecanoe-action/security/advisories/new)

2. **For issues in Tippecanoe itself**: Please report directly to the upstream repository at [felt/tippecanoe](https://github.com/felt/tippecanoe/security)

Please do not report security vulnerabilities through public GitHub issues.

## Security Considerations

This action downloads pre-compiled binaries from this repository's GitHub Releases. The binaries are built automatically from the official Tippecanoe source code using GitHub Actions runners.
