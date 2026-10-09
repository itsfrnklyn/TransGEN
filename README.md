# TransGEN

This repository is initialized for development. Application code and a technology
stack have not been added yet, so there are currently no dependencies to install,
services to start, or application tests to run.

## Branches

- `main`: the stable project baseline.
- `develop`: integration branch for ongoing development.

Create feature branches from `develop` and merge completed work back through a
pull request. Promote reviewed changes from `develop` to `main`.

## Getting started

Use the existing checkout at `/workspace/TransGEN` in the Codex cloud environment.
Each cloud task is already isolated; another Git worktree is unnecessary.

Check the current branch and working tree before making changes:

```sh
cd /workspace/TransGEN
git status --short --branch
```

When application code is added, document its prerequisites, installation,
startup, and test commands here. Keep credentials in environment settings or
ignored local environment files; commit only examples without secret values.
