# Agent guidance

This repository packages pyenv as a Zsh plugin.

## Development

- Keep package metadata and installation examples in `package.json` aligned with the repository's README.
- Validate changes with Zsh syntax checks for changed shell files; do not install the plugin into a user's live shell during validation.
- Load the `shell` skill before changing shell code.

## CI

- Before changing CI, inspect the current guidance in `pschmitt/ci-workflows`. Pin shared reusable workflow and action references to `@main`.
