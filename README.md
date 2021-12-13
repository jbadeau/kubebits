# kubebits

A [Backstage](https://backstage.io/) compatible, Kubernetes native software catalogue.

Kubits aims to provide the following features

- Backstage resource compatability
- RBAC authorization
- Micro frontend architecture
- Event bus for cross plug-in communication
- Java 17 backend
- CRD based
- Plugin registry
- Independent deployment
- Tekton based templates
- Operator based management

## Development

#### prerequisites*

- Java 17
- npm swagger-cli

#### Generate dereferenced json schema
`swagger-cli bundle -r .\Component.v1alpha1.schema.yaml -o output.yaml -t yaml`