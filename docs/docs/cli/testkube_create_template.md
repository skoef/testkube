## testkube create template

Create a new Template.

### Synopsis

Create a new Template Custom Resource.

```
testkube create template [flags]
```

### Options

```
      --body string            a path to template file to use as template body
  -h, --help                   help for template
  -l, --label stringToString   label key value pair: --label key1=value1 (default [])
  -n, --name string            unique template name - mandatory
      --template-type string   template type one of job|container|cronjob|scraper|pvc|webhook
      --update                 update, if template already exists
```

### Options inherited from parent commands

```
  -a, --api-uri string     api uri, default value read from config if set (default "https://demo.testkube.io/results/v1")
  -c, --client string      client used for connecting to Testkube API one of proxy|direct (default "proxy")
      --crd-only           generate only crd
      --namespace string   Kubernetes namespace, default value read from config if set (default "testkube")
      --oauth-enabled      enable oauth
      --verbose            show additional debug messages
```

### SEE ALSO

* [testkube create](testkube_create.md)	 - Create resource

