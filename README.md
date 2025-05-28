# Welcome to photoprism

[![App Status](https://argocd-internal.spirit-dev.net/api/badge?name=photoprism&revision=true&showAppName=true)](https://argocd-internal.spirit-dev.net/applications/photoprism)

## Table of content

[[_TOC_]]

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
