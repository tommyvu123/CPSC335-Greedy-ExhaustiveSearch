# CPSC 335 - Algorithm Engineering
# Project-2 - Container Ship Weight-maximization using Greedy/Exhaustive search algorithm

Tommy Vu tommyuv23@csu.fullerton.edu

**The Hypothesis**
This experiment will test the following hypotheses:
1. Exhaustive search algorithms are feasible to implement, and produce correct outputs.
2. Algorithms with exponential running times are extremely slow, probably too slow to be of
practical use


![image](https://github.com/tommyvu123/CPSC335-Greedy-ExhaustiveSearch/assets/91637834/33fab0da-43bf-496c-8fc0-a48864799699)

![image](https://github.com/tommyvu123/CPSC335-Greedy-ExhaustiveSearch/assets/91637834/cb441d16-1945-4f4a-b749-db9b2787b7a5)

![image](https://github.com/tommyvu123/CPSC335-Greedy-ExhaustiveSearch/assets/91637834/edcfc728-5cd8-47ec-a3f3-1c8331552d2e)


![image](https://github.com/tommyvu123/CPSC335-Greedy-ExhaustiveSearch/assets/91637834/7998a386-3f40-42f9-a1df-b018802e40fa)
![image](https://github.com/tommyvu123/CPSC335-Greedy-ExhaustiveSearch/assets/91637834/69fe9e41-ee2b-4040-9874-58cbfa1d414c)
![image](https://github.com/tommyvu123/CPSC335-Greedy-ExhaustiveSearch/assets/91637834/af8a5bce-17d8-4fb6-a0f9-01cb61a4feb1)

**A) Is there a noticeable difference in the performance of the two algorithms? Which is
faster, and by how much? Does this surprise you?**

There is a clear difference in the performance between the greedy algorithm and the
exhaustive search algorithm. This is no surprise because the greedy algorithm looks for
the most optimal path at each step, whereas the exhaustive search algorithm will look for
the overall best result.

**B) Are your empirical analyses consistent with your mathematical analyses? Justify
your answer.**

Yes, the empirical analysis is consistent with the mathematical analysis because for
greedy, we got a graph that showcases the O(n2) time complexity and for exhaustive, the graph matches that of an O(2n) graph.

**C) Is this evidence consistent or inconsistent with hypothesis 1? Justify your answer.**

Yes, the evidence is consistent with hypothesis 1, as they are feasible to implement and
they produce the correct outputs.

**D) Is this evidence consistent or inconsistent with hypothesis 2? Justify your answer.**

The evidence is consistent with hypothesis 2 as well because as seen in the graph, as n
gets larger, so does the time. This shows that algorithms with exponential running times
are extremely slow and not practical to use
