class Solution:
    def runningSum(self, nums: List[int]) -> List[int]:
        x =[]
        y = 0
        for i in nums:
            y +=i
            x.append(y)
        return x
