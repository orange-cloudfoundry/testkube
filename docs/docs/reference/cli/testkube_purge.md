## testkube purge

Uninstall Helm chart registry from current kubectl context

### Synopsis

Uninstall Helm chart registry from current kubectl context

```
testkube purge [flags]
```

### Options

```
  -h, --help               help for purge
      --name string        installation name (default "testkube")
      --namespace string   namespace from where to uninstall (default "testkube")
```

### Options inherited from parent commands

```
  -a, --api-uri string   api uri, default value read from config if set (default "http://localhost:8088")
  -c, --client string    client used for connecting to Testkube API one of proxy|direct (default "proxy")
      --oauth-enabled    enable oauth
      --verbose          show additional debug messages
```

### SEE ALSO

* [testkube](testkube.md)	 - Testkube entrypoint for kubectl plugin

