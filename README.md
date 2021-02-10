# unitarymerkle
(TODO...) I can in theory, offer a kind of math, or a kind of mathematical service, to help many existing systems work better together, at lower lag, higher bandwidth, without any extra dependence on me or any other system, just to fit such puzzles together better without being "a gatekeeper" etc.

Each node is adjacent to exactly 4 other nodes, in an infinite size undirected-graph. A topology with surprisingly many automorphisms compared to any other topology as far as I know, and each of them uniquely and bigO(1)-addressable by merkle/hash id

Imagine it as a 3-way infinite tree in all directions, and a clipboard/copy/paste node thats the 4th childs, and each node has a single bit of data, and 1 of 3/4 directions, and  4 possible actions (edge colors) from everywhere to 4 other places, navigating a superexponetial/tetration space compared to, what you might expect, a normal-exponential/sub-tetration space, such as 1 googol compared to 1 googolplex (and far beyond) is an exponential vs tetration level space.

The unique-id (other than by hash-collisions) is the 4-way forest id (hash of concat of 4 hashes) where each node stores 1 bit and has these 4 actions (each reversible by any palindrome of such 4 actions), of these actions: abcd->bcad (with flip of self bit), abcd-cbad (with flip of self bit), go forward and flip direction back toward where came from into  (is it a, c, or b?) (and of course still D), or swap c and d aka abcd->abdc. The first 3 of these possible actions allow storing a tree topology efficiency of bits of any data structure. The 4th possible action (instead of just 3) adds an exponential number of possible redundantly-cross-referencing paths from and to every possible state, without disturbing the merkle hashes. Surprisingly, while its still a merkle forest, which is something this has in common with blockchains and various security related algorithms, it has more than 1 path back to each previous state, most of which have nothing to do with the path taken from there to here, to get back to there. Surprisingly, any 2 (16+4+1)*256 bit merkle hash ids can be verified in bigO(1) to be adjacent or not adjacent, where each node is adjacent to exactly 4 other nodes (other than hash collisions), and this may, in theory, help in an optimizing mutex-related way, to improve performance between the sync of any subset of thousands of existing blockchains or subsets of any specific blockchain, or non-blockchain but still math-related algorithms or data-structures of some kind(s). I'm a mathematician and my main motivation in this is to help, whatever the world finds valuable to do together, to do that more efficiently and at lower lag. Lets try some experiments.
