# terminal

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)

A Helm chart for Kubernetes

**Homepage:** <https://github.com/NikolayMarusenko/terminal>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| KubeRocketCI |  | <https://github.com/epam/edp-install/> |

## Source Code

* <https://github.com/NikolayMarusenko/terminal>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repo | string | `"bitnami/kubectl"` |  |
| image.version | string | `"1.27.14"` |  |
| imagePullSecrets | list | `[]` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| replicaCount | int | `1` |  |
| resources.limits.cpu | string | `"64m"` |  |
| resources.limits.memory | string | `"64Mi"` |  |
| resources.requests.cpu | string | `"64m"` |  |
| resources.requests.memory | string | `"64Mi"` |  |
| serviceAccount.annotations | object | `{}` |  |
| serviceAccount.create | bool | `true` |  |
| serviceAccount.name | string | `""` |  |
| tolerations | list | `[]` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.13.1](https://github.com/norwoodj/helm-docs/releases/v1.13.1)