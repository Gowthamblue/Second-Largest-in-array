// User function template for C++ 
class Solution {
  public:
    // Function returns the second
    // largest elements
    int getSecondLargest(vector<int> &arr) {
        // Code Here
        int n=arr.size();
        sort(arr.begin(),arr.end());
        int max=arr[n-1];
        int smax=-1;
        for(int i=n-1;i>=0;i--)
        {
            if(arr[i]<max)
            {
                smax=arr[i];
                break;
            }
        }
        return smax;
    }
          
};
