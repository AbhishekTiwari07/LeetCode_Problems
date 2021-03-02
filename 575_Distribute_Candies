class Solution {
public:
    int distributeCandies(vector<int>& candyType) {
        long n = candyType.size();
        unordered_set<int> s1;
        for(int i=0;i<n;i++)
            s1.insert(candyType[i]);
        long m = s1.size();
        if(n/2 >= m)
            return m;
        else
            return n/2;
    }
};