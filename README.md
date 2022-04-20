# gitops-example-infra

This is a proof-of-concept repository. The repository contains a directory structure for managing multiple OpenShift clusters using GitOps. Each cluster can host multiple environments.

Create projects and application sets:

```
$ oc apply -R -f projects
```
