# new-tkc
This script automates the deployment of a new TKC.

usage: new-tkc [options]

Options:<br />
  -h                  : Display help<br />
  -n <ClusterName>    : Name of the cluster (required)<br />
  -N <namespace>      : Namespace (required)<br />

  -c <CPNodes>        : Number of Controller Nodes (required)<br />

  -w <WNodes>         : Number of Worker Nodes (required)<br />

  -t <template.yaml>  : Cluster template to use, defaults cluster-template.yaml<br />

  -f <formfactor>     : Formfactor of VMs<br />

