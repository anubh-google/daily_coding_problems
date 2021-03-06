# daily_coding_problems
problems:

1.Good morning! Here's your coding interview problem for today.
  This problem was recently asked by Google.
  Given a list of numbers and a number k, return whether any two numbers from the list add up to k.
  For example, given [10, 15, 3, 7] and k of 17, return true since 10 + 7 is 17.

2.Given an array of integers, return a new array such that each element at index i of the new array is
  the product of all the numbers in the original array except the one at i.
  For example, if our input was [1, 2, 3, 4, 5], the expected output would be [120, 60, 40, 30, 24].
  If our input was [3, 2, 1], the expected output would be [2, 3, 6]. follow up: you can't use division.
  
3.This problem was asked by Google.
Given the root to a binary tree, implement serialize(root), which serializes the tree into a string, and deserialize(s), which deserializes the string back into the tree.
For example, given the following Node class
class Node:
    def __init__(self, val, left=None, right=None):
        self.val = val
        self.left = left
        self.right = right
The following test should pass:
node = Node('root', Node('left', Node('left.left')), Node('right'))
assert deserialize(serialize(node)).left.left.val == 'left.left'

4. This problem was asked by Stripe.
   Given an array of integers, find the first missing positive integer in linear time and constant space. In other words, find the lowest positive integer that does not exist in      the array. The array can contain duplicates and negative numbers as well.
   For example, the input [3, 4, -1, 1] should give 2. The input [1, 2, 0] should give 3.
   You can modify the input array in-place.
   
   
5. This problem was asked by Jane Street.
   cons(a, b) constructs a pair, and car(pair) and cdr(pair) returns the first and last element of that pair. For example, car(cons(3, 4)) returns 3, and cdr(cons(3, 4)) returns 4. Given this implementation of cons:
def cons(a, b):
    def pair(f):
        return f(a, b)
    return pair
Implement car and cdr.
