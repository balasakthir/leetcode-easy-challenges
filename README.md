# leetcode-easy-challenges
In C language

Concatenation of Array -leetcode
Difficulty-easy

int* getConcatenation(int* nums, int numsSize, int* returnSize){
int* ans=(int *)malloc(sizeof (int)* numsSize* 2);
*returnSize=numsSize*2;
for(int i=0;i<numsSize;i++){
    ans[i]=ans[i+numsSize]=nums[i];
}
return ans;
}
