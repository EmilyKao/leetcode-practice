class Solution:
    @cache
    def climbStairs(self, n: int) -> int:
        
        if n == 1 :
            ans = 1
        if n == 2:
            ans = 2
        if n >=3:
            ans = self.climbStairs(n-2) + self.climbStairs(n-1)

        return ans
