# EditDistance
Compute the minimal edit distance between two strings.

This is a program in Java that solves the Edit Distance problem. 
We are given two strings A = a0a1 : : : am-1 and B = b0b1 : : : bn-1, and the
program compute the optimal sequence of edit operations that can transform A to B.
We allow ourselves three operations :
--insert(k,c) will insert a character c at the k’th position (between ak-1 and ak) in the string
A. The cost of this operation is Ci, a pre-defined constant that does not depend on
the inputs to insert.
--delete(k) will delete the k’th character (aj) of string A. The cost of this operation is Cd.
--replace(k,c) will replace the k’th character (ak) of string A with the character c. The cost
of this operation is Cr.

How to use: Download the .zip file and open it in a folder. In Main execute test4(cost1, cost2, cost3) to be given a list of operations that results in another string. cost1 is the cost of insertion, cost2 deletion and cost3 replacement. You can change these values as you want and modify the strings you're working on in the test4 function. 
