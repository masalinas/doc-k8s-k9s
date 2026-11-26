# Description
DoC k9s kubernetes TUI management

## Steps

- **STEP01**: Install k9s in Linux
```shell
$ curl -sL https://github.com/derailed/k9s/releases/latest/download/k9s_Linux_amd64.tar.gz | tar -xz k9s
$ sudo mv k9s /usr/local/bin/
```

- **STEP02**: Execute k9s
k9s will use the current context configured in your default .kube/config to connect to a kubernetes cluster
```shell
$ k9s
```

![k9s TUI](images/tui.png)


