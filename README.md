# r5flames

[View before](https://buma.github.io/r5flames/r5_before.html)
This is with short-circuited angle calculations:[View after](https://buma.github.io/r5flames/r5_after.html)

How to [interpret it](http://www.brendangregg.com/blog/2014-06-12/java-flame-graphs.html)

Mouse over elements to see details. 

The y-axis is stack depth, and the x-axis spans the sample population. Each rectangle is a stack frame. Color is not important, it's randomized to differentiate frames. The ordering from left to right is also unimportant.

You look for the widest frames, from bottom up, and forks in the "flames", which indicate different code paths taken. 

the percentage is inclusive of all child frames above it).
