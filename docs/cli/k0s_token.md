## k0s token

Manage join tokens

```
k0s token [flags]
```

### Options

```
  -h, --help                help for token
      --kubeconfig string   path to kubeconfig file [$KUBECONFIG]
```

### Options inherited from parent commands

```
  -c, --config string            config file (default: ./k0s.yaml)
      --data-dir string          Data Directory for k0s (default: /var/lib/k0s). DO NOT CHANGE for an existing setup, things will break!
  -d, --debug                    Debug logging (default: false)
  -l, --logging stringToString   Logging Levels for the different components (default [kube-controller-manager=1,kube-scheduler=1,kubelet=1,etcd=info,containerd=info,konnectivity-server=1,kube-apiserver=1])
```

### SEE ALSO

* [k0s](k0s.md)	 - k0s - Zero Friction Kubernetes
* [k0s token create](k0s_token_create.md)	 - Create join token

