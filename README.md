# Transform-Array-by-Parity
class Solution:
    def transformArray(self, nums: List[int]) -> List[int]:
        if nums is None:
            return None
        r=[]
        for i in nums:
            if i%2==0:
                r.append(0)
            else:
                r.append(1)
        r.sort()
        return r
