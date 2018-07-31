# leetcode
#array 两数之和
#思路：
#用target-nums=new
#检测new中元素是否在nums中
  class Solution:
      def twoSum(self, nums, target):
          """
          :type nums: List[int]
          :type target: int
          :rtype: List[int]
          """
          new=[target-i for i in nums]
          mset=set(nums)
          for i,num in enumerate(new):
              if num in mset and i!=nums.index(num):
                  return i,nums.inde
