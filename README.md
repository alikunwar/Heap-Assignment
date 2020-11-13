# Heap-Assignment

Implementation of malloc and free. 
Implement a library that interacts with the operating system to perform heap management on behalf of a user process.

The code compiles into four shared libraries and six test programs. 

$ env LD_PRELOAD=lib/libmalloc-ff.so tests/test1 

To run the other heap management schemes replace libmalloc-ff.so with the appropriate
library:
Best-Fit: libmalloc-bf.so
First-Fit: libmalloc-ff.so
Next-Fit: libmalloc-nf.so
Worst-Fit: libmalloc-wf.so
