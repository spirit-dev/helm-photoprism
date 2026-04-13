# photoprism

[![GitLab Sync](https://img.shields.io/badge/gitlab_sync-photoprism-blue?style=for-the-badge&logo=gitlab)](https://gitlab-internal.spirit-dev.net/github-mirror/helm-photoprism) <!-- markdownlint-disable MD041 -->
[![GitHub Mirror](https://img.shields.io/badge/github_mirror-photoprism-blue?style=for-the-badge&logo=github)](https://github.com/spirit-dev/helm-photoprism)
[![App Status](https://argocd-internal.spirit-dev.net/api/badge?name=photoprism&revision=true&showAppName=true)](https://argocd-internal.spirit-dev.net/applications/photoprism)

<!--TOC-->

- [Installation process](#installation-process)
- [Cli options](#cli-options)

<!--TOC-->

## Installation process

The installation is entirely managed by Argocd.

A `Makefile` is present here to ease the first and one-time deployment or in case of an issue.
The installation should be done in two steps:

```shell
#> make dry-run ENV=<ENV>
#> make install ENV=<ENV>
```

## Cli options

Some commands like user management will be available via CLI

1. Jump in a photoprism pod `kex <pod> -n ns sh`

2. Execute cli commands: `photoprism help` for more information.

Documentation [available here](https://docs.photoprism.app/user-guide/users/cli/)
