---
layout: post
title:  "(Currently writing) Suffix trees and palindromes oh my!"
date:   2020-08-27 12:41:00 -0400
categories: SuffixTrees Palindromes Leetcode academia
---

*This post is still under construction.*  
*Come back later once it is complete!*

# Suffix trees and palindromes oh my! 
Recently on Leetcode I ran across [the problem of finding the largest palindrome substring](https://leetcode.com/problems/longest-palindromic-substring/). After giving what I thought was a very nifty dynamic programming solution that ran in `O(n^2)` time and `O(n^2)` space,  I was shocked to learn that there was in fact a linear-time solution! In 1975 Glenn Manacher discovered a linear algorithm to find all of the palindromes at the start of a string, and in 1995 Alberto Apostolico, Dany Breslauer, and Zvi Galil expanded the algorithm to find all of the palindromes in the string, still in linear time ([Source](https://en.wikipedia.org/wiki/Longest_palindromic_substring)). What I'm curious about however are the linear time solutions that involve suffix trees such as published in Dan Gusfield’s book *Algorithms on Strings, Trees, and Sequences*.

So, let's dig into suffix trees and palindromes, and see if we can't drive our own linear time algorithm for finding palindromic substrings!

## Palindromes
## Suffix trees
