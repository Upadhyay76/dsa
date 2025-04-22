class Solution {  
    public int missingNumber(int[] nums) {  
        int n = nums.length;  
       int eps=(n*(n+1)/2); 
       int res=0;
       for(int num:nums){
        res+=num;
       }
       return eps-res; 
    }  
}  
