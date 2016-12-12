# cmpt711

The code in this repository builds a pipeline that takes align.txt & talign.txt (the assumptions CHARSET portion of align.txt) and does the following:

1. align.phy: organize, seperate, combine alignments from different genes. Does the same with muscel alignments for comparison.
2. build phylogeny
2.1 raxml.phy: creates raxml phylogeny from alignments made from previous step.
2.2 beast
2.3 Note: bash versions (.sh) files are also available for raxml and beast and lists all files needed to be processed such that they can be seperated and run on different machines if necessary. They may also be embedded into (.pbs) files for submission as jobs on a cluster.
