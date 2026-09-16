# SCC IT Toolkit Updates

Public update channel for **EnterpriseToolkit-MultiUnit / SCC IT Toolkit**.

This repository contains update metadata and release packages only. It does **not** contain the private application source code, credentials, local configuration, databases, logs, or environment-specific data.

## Update model

The installed Toolkit checks `update.json` to determine whether a newer version is available.

For the current single-file PyInstaller architecture, an application-code update replaces only the deployed application executable. The full installer and private source tree are not required for normal in-app updates.

Each published package must be verified against the SHA-256 value in `update.json` before it is installed.

## Files

- `update.json` — current update channel metadata.
- `releases/` — release package documentation / packages.

## Security

Do not publish passwords, API keys, environment settings, domain credentials, private certificates, local databases, logs, or user-specific configuration in this repository.
