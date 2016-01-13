# Graph-kernels

In the real world similarity between graphs is an important measure needed
for several real life problems like classification of Proteins and Enzymes and
even in the Social Network analysis whereby 2 social graphs might have to
be clustered by similar properties.
In the quest to determine the similarity between pairs of graphs in 2005,
Borgwardt et al looked at the similarity between the graphs in terms
of shortest path kernels which was an improvement over the random walk
kernels over product graphs which had its limitations on tractability but in
2010, SVN Vishwanathan et al came up with a novel method to compute
random walk kernels upto any length and that became much faster in terms
of computation than the Shortest Path Kernel .
We looked at the 2010 paper and implemented the methods for computing
the random walk kernel that were used in the paper and also implemented the
shortest path kernel as shown by the 2005 paper and compared the running
times and the kernels obtained from them.
