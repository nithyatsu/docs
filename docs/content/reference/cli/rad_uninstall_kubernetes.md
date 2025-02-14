---
type: docs
title: "rad uninstall kubernetes CLI reference"
linkTitle: "rad uninstall kubernetes"
slug: rad_uninstall_kubernetes
url: /reference/cli/rad_uninstall_kubernetes/
description: "Details on the rad uninstall kubernetes Radius CLI command"
---
## rad uninstall kubernetes

Uninstall Radius from a Kubernetes cluster

### Synopsis

Uninstall Radius from a Kubernetes cluster.

```
rad uninstall kubernetes [flags]
```

### Examples

```
# uninstall Radius from the current Kubernetes cluster
rad uninstall kubernetes

# uninstall Radius from a specific Kubernetes cluster based on the Kubeconfig context
rad uninstall kubernetes --kubecontext my-kubecontext
```

### Options

```
  -h, --help                 help for kubernetes
      --kubecontext string   The Kubernetes context to use, will use the default if unset
      --purge                Delete all data stored by Radius.
```

### Options inherited from parent commands

```
      --config string   config file (default "$HOME/.rad/config.yaml")
  -o, --output string   output format (supported formats are json, table) (default "table")
```

### SEE ALSO

* [rad uninstall]({{< ref rad_uninstall.md >}})	 - Uninstall Radius for a specific platform

