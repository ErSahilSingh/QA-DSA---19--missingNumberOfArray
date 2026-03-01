# QA-DSA---19--missingNumberOfArray

var missingNumber = function(nums) {
  let  Totallength= nums.length
   let totalsum= Totallength*(Totallength+1)/2
   let actualcount=0
   for(let i=0;i<Totallength;i++){
    actualcount=actualcount+nums[i]
   }
   return totalsum-actualcount
    
};
