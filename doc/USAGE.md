
## Usage
The following assumes you have the plugin installed via

```shell
oc krew install monit
```

### Interact with monitoring stack of a cluster in your current kubecontext

```shell
oc monit
```

### Scan images in another kubecontext

```shell
oc monit --context=context-name
```

## How it works
`monit` helps you to interact with the built-in monitoring stack. It allows 
you to do the following things quickly from the CLI;
* get Prometheus route
* get Grafana Route
* get Alertmanager route
* get all firing alerts (can be grouped by severity)