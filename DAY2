# Ram-Ram-Bhai-Sareya-Ne-With-Frienducation-Tanishka--Jha-
75 ques challenge

//MISSING NUMBER
class Solution {
public:
    int missingNumber(vector<int>& nums) {
        if(nums.size()==0)
        {
            return 0;
        }
        sort(nums.begin(),nums.end());
            for(int i=0;i<nums.size();i++)
            {
                if(nums[i]!=i)
                {
                    return i;
                }
            }
return nums.size();
    }
};

//BEST TIME TO BUY AND SELL

class Solution {
public:
    int maxProfit(vector<int>& prices) {
        int a=prices.size();
        if (a==0)
        return 0;
vector<int>profit(a);
vector<int>buy(a);
int maximumProfit =0;
 profit[0]=0;
 buy[0]=prices[0];
 for(int i=1;i<a;i++)
 {
     profit[i]=max(0, prices[i]-buy[i-1]);
     maximumProfit = max(maximumProfit,profit[i]);
     if(profit[i]==0)
     {
         buy[i]=prices[i];
     }
     else
     buy[i]=buy[i-1];

 }
return maximumProfit;
        
    }
};
