# Renovate Config

Shared Renovate Bot Config Preset

## Features

- Groups all non-major updates into a single PR
- Semantic commit messages with `chore` type
- Major updates require Dependency Dashboard approval
- Minor, patch, pin, and digest updates are automerged on schedule by Renovate itself (`platformAutomerge: false`), so no repository needs GitHub auto-merge enabled
- Lock file maintenance runs weekly (Monday before 3am)
- Vulnerability alerts are enabled and labeled with `security`
