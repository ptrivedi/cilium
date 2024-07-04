<!-- This file was autogenerated via cilium cmdref, do not edit manually-->

## cilium-dbg troubleshoot clustermesh

Troubleshoot connectivity towards remote clusters

```
cilium-dbg troubleshoot clustermesh [clusters...] [flags]
```

### Options

```
      --clustermesh-config string    Path to the ClusterMesh configuration directory (default "/var/lib/cilium/clustermesh/")
  -h, --help                         help for clustermesh
      --timeout duration             Timeout when checking connectivity to a given cluster (default 5s)
      --without-service-resolution   Disable k8s service to IP resolution through the k8s client
```

### Options inherited from parent commands

```
      --config string   Config file (default is $HOME/.cilium.yaml)
  -D, --debug           Enable debug messages
  -H, --host string     URI to server-side API
```

### SEE ALSO

* [cilium-dbg troubleshoot](cilium-dbg_troubleshoot.md)	 - Run troubleshooting utilities to check control-plane connectivity
