# FastTree

FastTree is a method for constructing large phylogenetic trees and for estimating their reliability. It improves neighbor joining algorithms by using sequence profiles instead of distance matrices, reducing both the amount of space and time required for the calculation of large phylogenetic trees. Using multiple heuristics, the number of profiles that are considered for each join of the neighbor joining algorithm can be kept small. In the end, the topology is further improved by nearest neighbor interchanges. 

Further, using sequence profiles instead of distance matrices enables local bootstrapping in order to evaluate the quality of joins. Even though local bootstrapping is weaker than global boostrapping, local bootstrapping is multiple orders of magnitudes faster.

## Contents of the demo

A working demo for [`FastTree`](fasttree.ipynb). The demo shows how to

1. install fasttree
2. display usage instructions for fasttree
3. run fast tree on a multiple sequence alignment of amino acid sequences
4. visualize the resulting phylogenetic trees
