# renovate-configs

Shared config files for Renovate Bot - https://renovatebot.com/docs/

These config files are used across a range of sites and projets to manage Renovate dependency management pull requests.

## `only-hashicorp.json`

This is a very specific config that _only_ opens PRs for updated packages within the `@hashicorp` NPM ogranization. This config is primarily used to automate updates from our [`web-components` repo](https://github.com/hashicorp/web-components)
