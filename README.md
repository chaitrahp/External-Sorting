# External-Sorting

External sorting is a term for a class of sorting algorithms that can handle massive amounts of data.
External sorting is required when the data being sorted do not fit into the main memory of a computing 
device (usually RAM) and instead they must reside in the slower external memory (usually a hard drive).
It typically uses a hydrid sort-merge strategy. In the sorting phase, chunks of data small enough to fit in 
main memory are read, sorted, and written out to a temporary file. In the merge phase, the sorted sub-files
are combined into a single larger file. External sorting will access items in sequential order and it also 
minimizes the access times. It is a stable sorting technique. By performing External Sort, we can use the
multiple disk drives parallely (in order to improve sequential read and write speed), and it will increase
the speed of both hardware and software.
