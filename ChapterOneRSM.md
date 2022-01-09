# Part I - Foundation of Data Systems

## Chapter1. Reliable, Scalable, and Matainable Applications
+ An important idea is that `data-intersive` and `compute-intensive` are two different things
+ There are 3 aspects for limitation of applications: `amount of data` , `complexity of data`, `speed at which data is changing`
+ There are 5 functions for applications:
  +   databases
  +   caches
  +   search indexes
  +   stream processing
  +   batch processing
> From the book:
> + store data so that they, or another application, can find it again later (*databases*)
> + remember the result of an expensive operation, to speed up reads (*caches*)
> + allow users to search data by keyword of filter it in various way (*search indexes*)
> + send a message to another process, to be handled asynchronously (*stream processing*)
> + periodically crunch a large amount of accumulated data (*batch processing*)

So based on the previous aspect, different databases varies.
