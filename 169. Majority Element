class Solution {
    public int majorityElement(int[] nums) {
        Map<Integer,Integer> map=new LinkedHashMap<>();
        for(int i=0;i<nums.length;i++){
            map.put(nums[i],map.getOrDefault(nums[i],0)+1);
        }
        for(Integer k:map.keySet()) {
            if(map.get(k)>nums.length/2) return k; 
        }
        return 0;
    }
}
