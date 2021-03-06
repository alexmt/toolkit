## tk export source

Export sources

### Synopsis

The export source sub-commands export sources in YAML format.

### Options

```
  -h, --help               help for source
      --with-credentials   include credential secrets
```

### Options inherited from parent commands

```
      --all                 select all resources
      --kubeconfig string   path to the kubeconfig file (default "~/.kube/config")
      --namespace string    the namespace scope for this operation (default "gitops-system")
      --timeout duration    timeout for this operation (default 5m0s)
      --verbose             print generated objects
```

### SEE ALSO

* [tk export](tk_export.md)	 - Export resources in YAML format
* [tk export source git](tk_export_source_git.md)	 - Export GitRepository sources in YAML format
* [tk export source helm](tk_export_source_helm.md)	 - Export HelmRepository sources in YAML format

