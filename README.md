# Useful Algorithms
A list of useful algorithms and their documentation/code. Listing algorithms I come across that may be useful in the future:

## Neighbor Searching

* ANNOY https://github.com/spotify/annoy - Approximate Nearest Neighbor Oh Yeah! Uses a tree to divide the n-dimensional space and search for neighbors. Advantage is that the search index is a static file that can be shared and distributed across many workers.
* DISCO https://blog.twitter.com/2012/dimension-independent-similarity-computation-disco - Dimension Independent Similarity Computation - Uses MapReduce to find similar items. Implements a custom sampler, such that the output value is the expectation of the cosine similarity between users.
* DIMSUM https://blog.twitter.com/2014/all-pairs-similarity-via-dimsum - Dimension Independent Matrix Square using MapReduce - Replaces DISCO. Still a map-reduce algorithm with a more efficient mapper step.
