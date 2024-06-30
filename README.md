This repository contains simple templates for automatic YAKKO builds of OpenShift clusters.

**For more info:**
- visit [YAKKO](https://github.com/ozchamo/YAKKO)
- check out installation and usage when ready
- issue 'yakko buildfromtemplate \<raw-file-of-template-in-this-repo\>'  
  noting that the template needs to be the raw file offered by GitHub
- example: to build a 1m+2w OpenShift cluster with OCP and NFS automatically:  
  yakko buildfromtemplate https://raw.githubusercontent.com/ozchamo/yakko-build-templates/main/1m%2B2w-ocpvirt

**Some templates fournd here:**
- sno - builds a Single Node OpenShift with 32GB as cluster 'sno.localdomain'
- 1m+2w-ocpvirt - builds a cluster with 1 master and 2 workers and installs OpenShift Virtualization using NFS oon the yakko host as 'ocpvirt.localdomain'
- 3m+0w - builds a compact cluster with 3 masters and no workers as 'compactcluster.localdomain'

NOTE!**
These cluster shapes are not restrictive. You can add and delete worker nodes as you see fit.
