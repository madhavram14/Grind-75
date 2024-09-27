Leetcode Grind 75

This repository contains solutions to Leetcode problems as part of the Grind 75 set, curated by the creator of the popular Blind 75 to practice data structures and algorithms (DSA). You can find the full list of questions here.
Problem Solutions
1. Two Sum

Problem Description:
Given an array of integers nums and an integer target, the goal is to find two numbers in the array that sum up to the target. You must return the indices of the two numbers.

Approach:
Initially, I solved this problem using a brute force approach with a nested loop to compare every possible pair of numbers in the array. This method works but has a time complexity of O(N^2), making it inefficient for larger arrays.

After some research, I discovered a more efficient solution using a dictionary (hash map) to store the indices of the numbers. This allows the problem to be solved in O(N) time, as we can find the complement of the current number in constant time using the hash map.
