# bestfit
Best Fit Code
1- Input memory blocks and processes with sizes.
2- Initialize all memory blocks as free.
3- Start by picking each process and find the
   minimum block size that can be assigned to
   current process i.e., find min(bockSize[1], 
   blockSize[2],.....blockSize[n]) > 
   processSize[current], if found then assign 
   it to the current process.
5- If not then leave that process and keep checking
   the further processes.
