## helm repo

add, list, remove, update, and index chart repositories

### Synopsis



This command consists of multiple subcommands to interact with chart repositories.

It can be used to add, remove, list, and index chart repositories.
Example usage:
    $ helm repo add [NAME] [REPO_URL]


### Options inherited from parent commands

```
      --debug                     enable verbose output
      --home string               location of your Helm config. Overrides $HELM_HOME (default "$HOME/.helm")
      --host string               address of Tiller. Overrides $HELM_HOST
      --kube-context string       name of the kubeconfig context to use
      --tiller-namespace string   namespace of Tiller (default "kube-system")
```

### SEE ALSO
* [helm](helm.md)	 - The Helm package manager for Kubernetes.
* [helm repo add](helm_repo_add.md)	 - add a chart repository
* [helm repo index](helm_repo_index.md)	 - generate an index file given a directory containing packaged charts
* [helm repo list](helm_repo_list.md)	 - list chart repositories
* [helm repo remove](helm_repo_remove.md)	 - remove a chart repository
* [helm repo update](helm_repo_update.md)	 - update information of available charts locally from chart repositories

###### Auto generated by spf13/cobra on 23-Jun-2017
