What is a LRU Cache?
A Least Recently Used (LRU) Cache organizes items in order of use, allowing you to quickly identify which item hasn't been used for the longest amount of time. Picture a clothes rack, where clothes are always hung up on one side. To find the least-recently used item, look at the item on the other end of the rack.


Why even use a Cache?
Say you're managing a cooking site with lots of cake recipes. As with any website, you want to serve up pages as fast as possible.

When a user requests a recipe, you open the corresponding file on disk, read in the HTML, and send it back over the network. This works, but it's pretty slow, since accessing disk takes a while.

Ideally, if lots of users request the same recipe, you'd like to only read it in from disk once, keeping the page in memory so you can quickly send it out again when it's requested. Bam. You just added a cache.

A cache is just fast storage. Reading data from a cache takes less time than reading it from something else (like a hard disk).


Complexity Analysis

Costs	        Worst Case
Space	           O(n)
Get LRU item	   O(1)
Access Item	       O(1)



About this project
This project offers a fast and optimized implementation LRU cache in C Uses Double hashing for most the efficient implementation. The code is well documented and every function and variable is named in way that makes it easy to understand.
