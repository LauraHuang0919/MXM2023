# MXM2023
This project aims to investigate whether Long Branch Attraction (LBA) introduces bias to MLE in
phylogenetic tree reconstruction even for simple evolutionary models and small-scale trees. Specifically, we
aim to compute the optimality conditions (i.e. the tree parameters that give the maximum likelihood) of
all possible configurations for the unrooted four-species tree with two long branches through a combination
of analytical solutions to the MLE equation and minimization software. After implementing a Homotopy
Continuation approach and a Least Squares Optimization approach in Julia, we find that the results from
the two methods only agrees at certain boundary cases. The homotopy continuation methods do not yield
real solutions when there are two extremely long branches. Although we work out a case of the quartet 13|24
and find that homotopy continuation method only produce real solutions when the dataset satisfies some
constraints, further research into the inconsistencies between two methods is needed.
