## Cluster-Tools

### Description

Cluster-Tools is a collection of useful BASH scripts developed by Research Computing @ Rochester Institute of Computing. These scripts are meant to help both admins and users in their interactions with the SLURM cluster manager.

### Commands

#### cluster-fork [-s] "ps aux | wc -l"

##### Description

Executes a single command across all of the nodes listed in SLURM.

##### Options

-s : Perform this action silently by writing the output from each host to a file names <host>.out

#### cluster-free

##### Description

Shows a list of the available cores and memory for each node in the cluster. Nodes with no available cores are hidden.

##### Options

-a : Show all nodes, even those that are completely allocated

#### cluster-used

##### Description

Shows a list of the allocated cores and memory for each node in the cluster. Nodes with no allocated cores are hidden.

##### Options

-a : Show all nodes, even those that are completely unallocated

## Authors
* Bryan T. Meyers (datadrake)
