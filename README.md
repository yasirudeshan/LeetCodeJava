# LeetCodeJava
solving leetcode problems using Java.


1. Two Sum Problem

lass Solution {
    public int[] twoSum(int[] nums, int target) {
        int[] arr = new int[2];

        for(int i = 0; i < nums.length; i++){
            for(int j = 0; j < nums.length; j++){
                if(i != j){
                    if(nums[i] + nums[j] == target){
                    arr[0] = j;
                    arr[1] = i;
                    }
                }

            }
        }
        return arr;
    }
}
