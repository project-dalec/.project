# .project - Dalec

This repository contains standardized metadata for the [Dalec](https://github.com/project-dalec/dalec) project, following the [CNCF `.project` specification](https://github.com/cncf/automation/tree/main/utilities/dot-project).

## What is Dalec?

Dalec lets you produce secure packages and containers with declarative configurations. It leverages BuildKit to build Linux packages (RPM, DEB) and container images from YAML specifications.

## Files

| File | Purpose |
|------|---------|
| `project.yaml` | Core project metadata (description, repositories, maturity, social links, etc.) |
| `maintainers.yaml` | Maintainer roster with GitHub handles |
| `SECURITY.md` | Security policy and vulnerability reporting |
| `LICENSE` | Apache License 2.0 |

## Validation

Project metadata is automatically validated on every pull request and push to `main` using the [CNCF validation actions](https://github.com/cncf/automation).

## Links

- **Website:** <https://project-dalec.github.io/dalec/>
- **Main Repository:** <https://github.com/project-dalec/dalec>
- **CNCF Sandbox Application:** <https://github.com/cncf/sandbox/issues/396>
