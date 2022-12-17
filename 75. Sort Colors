class Solution {
    public void sortColors(int[] nums) {
        int f=0,s=0,t=0,len=nums.length;
        for(int i:nums){
            if(i==0) f++;
            if(i==1) s++;
            if(i==2) t++;
        }
        for(int i=0;i<len;++i){
            if(i<f){nums[i]=0; continue;}
            else if(i<f+s){nums[i]=1;continue;}
            else nums[i]=2;
        }
    }
}
