# kubebits

A Kubernetes native, [Backstage](https://backstage.io/) compatible, DevOps portal.

Kubebits aims to provide the following:

- All in one K3S & PostgreSQL image
- CRD based catalog store
- Container based plugins
- Operator based management
- RBAC
- Micro frontend architecture
- Context awarenesss

## Prerequisites

- Earthly
- Docker/Podman

Generate dereferenced json schema
`swagger-cli bundle -r .\Component.v1alpha1.schema.yaml -o output.yaml -t yaml`
