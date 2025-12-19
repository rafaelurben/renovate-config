# renovate-config

This repository defines an org-level (user-level) default [renovate bot](https://docs.renovatebot.com/) configuration.

Files:

- `default.json`: Defines the global preset config. Automatically used when this repository is used as a preset.
- `org-inherited-config.json`: All renovate configs in this user/org [automatically inherit](https://docs.renovatebot.com/mend-hosted/hosted-apps-config/#inherited-config) from this.
- `renovate.json`: Renovate config for this repository.


## Self-hosted renovate

- https://docs.renovatebot.com/getting-started/running/
- https://docs.renovatebot.com/self-hosted-configuration/
- https://docs.renovatebot.com/modules/platform/github/#running-as-a-github-app
- https://docs.github.com/en/actions/reference/workflows-and-actions/workflow-syntax
