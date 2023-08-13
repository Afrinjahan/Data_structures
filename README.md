# Data_structures
## LinkedList Practice problems
1. Insert into and delete from a single sorted Linked List.
3. Print the contents of a simple linked list in reverse order using recursion.
4. Merge two sorted Linked List.
5. Find the median of a sorted Linked List.

## Array practice problems
1. Given an array of size  such that it only contains distinct integers in the range of . Find the missing element.

Input : 
N = 5
arr: A[] = {1,2,3,5}
Output:  4

2. Given an array  and an integer  where K is smaller than size of array, the task is to find the  element in the given array. It is given that all array elements are distinct.
 :-   and  denotes the  and  index of the array.


N = 6 
arr[] = 7 10 4 3 20 15 
K = 3 
Output    7 

3rd smallest element in the given
array is 7.
3. Given an array a[] of size N which contains elements from 0 to N-1, you need to find all the elements occurring more than once in the given array. Return the answer in ascending order.
 The extra space is only for the array to be returned.
Try and perform all operations within the provided array. 

N = 4
a[] = {0,3,1,2}
 Output: -1

4. Given string str, find the length of the longest repeating subsequence such that it can be found twice in the given string.
The two identified subsequences A and B can use the same ith character from string str if and only if that ith character has different indices in A and B. For example, A = "xax" and B = "xax" then the index of first "x" must be different in the original string for A and B.


str = "axxzxy"
2 

The given array with indexes looks like 
a x x z x y 
0 1 2 3 4 5 

 
The longest subsequence is "xx".
It appears twice as explained below. 
 
 
x x 
0 1 <-- index of subsequence A 
------ 
1 2 <-- index of str 

We are able to use character 'x'
(at index 2 in str) in both subsequences
as it appears on index 1 in subsequence A
and index 0 in subsequence B.
