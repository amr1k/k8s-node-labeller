# K8S Node Labeller
This repo provides an example of how a k8s node can be labelled automatically using a daemonset (applied via gitops)

This can be applied using kubectl:

```
kubectl create -f node-labeller-ds.yaml
```

or using gitops (preferred):

https://cloud.google.com/anthos-config-management/docs/how-to/install-anthos-config-management

note: this example uses bitnami/kubectl image, any/custom image that bundles kubectl can be used.
