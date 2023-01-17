# new-tkc
This script automates the deployment of a new TKC.

...
usage: new-tkc [options]

Options:
  -h                  : Display help<br />
  -n <ClusterName>    : Name of the cluster (required)
  -N <namespace>      : Namespace (required)

  -c <CPNodes>        : Number of Controller Nodes (required)

  -w <WNodes>         : Number of Worker Nodes (required)

  -t <template.yaml>  : Cluster template to use, defaults cluster-template.yaml

  -f <formfactor>     : Formfactor of VMs

...

