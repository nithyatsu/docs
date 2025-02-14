---
type: docs
title: "rad application status CLI reference"
linkTitle: "rad application status"
slug: rad_application_status
url: /reference/cli/rad_application_status/
description: "Details on the rad application status Radius CLI command"
---
## rad application status

Show Radius Application status

### Synopsis

Show Radius Application status, such as public endpoints and resource count. Shows details for the user's default application (if configured) by default.

```
rad application status [flags]
```

### Examples

```

# Show status of current application
rad app status

# Show status of specified application
rad app status my-app

# Show status of specified application in a specified resource group
rad app status my-app --group my-group

```

### Options

```
  -a, --application string   The application name
  -g, --group string         The resource group name
  -h, --help                 help for status
  -o, --output string        output format (supported formats are json, table) (default "table")
  -w, --workspace string     The workspace name
```

### Options inherited from parent commands

```
      --config string   config file (default "$HOME/.rad/config.yaml")
```

### SEE ALSO

* [rad application]({{< ref rad_application.md >}})	 - Manage Radius Applications

