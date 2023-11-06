# Entrywan kubernetes conformance tests

## Create cluster

From the [Entrywan portal](https://portal.entrywan.com/kubernetes),
click on "Add cluster":

![one-click install](https://www.entrywan.com/img/doc-cluster.png)

Once the cluster is running, click "kubeconfig" and then the "copy"
icon to insert the kubeconfig onto the clipboard.  Paste those
contents into `~/.kube/config`.

## Run tests

```sh
sonobuoy run --mode=certified-conformance
```
