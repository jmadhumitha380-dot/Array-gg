# Array-gg
Practice program
class Solution:
    def missingNum(self, arr):
        n = len(arr) + 1
        total = n * (n + 1) // 2
        arr_sum = sum(arr)
        return total - arr_sum
Output:
Input: 
arr[] = 1 2 3 5
Output:
4
