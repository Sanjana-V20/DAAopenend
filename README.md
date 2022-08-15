# DAA openend

Java program showing implementation of Tag sort

When we are operating on large array of objects, it might be too costly to swap these large object.

Tag sort is used when we need to avoid swapping of large objects or need to access elements of a large array in both original and sorted orders. 

1. Tag Sort allows sorting an integer array after tagging it with original object.
2. In turn, we only swap the tag array integers instead of large array of objects.
3. The actual elements are not being changed during the sort process. The positions in the tag array are being changed so they will hold the correct ordering of the elements when they are sorted.
