# Nodes
Node Replication between sockets/cpus with Flat Combining between cores in a cpu

As in NrOS (https://www.usenix.org/system/files/osdi21-bhardwaj.pdf)

Synchronize key data structures across a non-uniform memory access (NUMA) system. Introduce a Nodes module allowing an Oberon loop per core, FC per loop in a node, CNR between nodes in a machine, distributed consensus over a cluster of machines
