# Power-of-Two
Given an integer n, return true if it is a power of two. Otherwise, return false.  An integer n is a power of two, if there exists an integer x such that n == 2x.

class Solution:
    def isPowerOfTwo(self, n: int) -> bool:

        for i in range(-31,32):
            if n==(2**i):
                return True
