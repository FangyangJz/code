## Flattening an arbitrarily deep list (or any iterator)Originally published: 2012-04-03 16:21:31 
Last updated: 2012-04-03 17:13:35 
Author: Garrett  
 
What if you had a list like this: [1, -10, [1,2,[3,4]], xrange(200)], and you just wanted to go through each element in order (wanted it to return a simple list of [1,-10,1,2,3,4,1,2,3,4...199])