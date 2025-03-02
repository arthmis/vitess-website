---
title: GetWorkflows
series: vtctldclient
commit: d3ff5982ddbbb04da1c9ac3c0bff9b09c904c749
---
## vtctldclient GetWorkflows

Gets all vreplication workflows (Reshard, MoveTables, etc) in the given keyspace.

```
vtctldclient GetWorkflows <keyspace>
```

### Options

```
  -h, --help           help for GetWorkflows
      --include-logs   Include recent logs for the workflows. (default true)
  -a, --show-all       Show all workflows instead of just active workflows.
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --server string             server to use for the connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

