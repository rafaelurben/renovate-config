# renovate-config

This repository defines an org-level (user-level) default [renovate bot](https://docs.renovatebot.com/) configuration.

Renovate itself is run via GitHub Actions from a private repository.

## Files

- `default.json`: Defines the global preset config. Automatically used when this repository is used as a preset.
- `renovate.json`: Renovate config for this repository.

Previously removed files:

- `org-inherited-config.json`: All renovate configs in this user/org [automatically inherit](https://docs.renovatebot.com/mend-hosted/hosted-apps-config/#inherited-config) from this when run via Mend-hosted renovate.
