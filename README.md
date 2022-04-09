# subset

### In this we understand how to generate subset of any given array

#### firstly we will understand how to create subset : 
1. Create a recursive function that takes the following parameters, input array, the current index, the output array, or current subset, if all the subsets need to be stored then a vector of the array is needed if the subsets need to be printed only then this space can be ignored.


2. if the current index is equal to the size of the array, then print the subset or output array or insert the output array into the vector of arrays (or vectors) and return.

3. There are exactly two choices for very index.
4. Ignore the current element and call the recursive function with the current subset and next index, i.e i + 1.
5. Insert the current element in the subset and call the recursive function with the current subset and next index, i.e i + 1.

#####Code

```c++
#include <bits/stdc++.h>
using namespace std;
#define int long long
#define float double
#define pb push_back
#define mp make_pair
#define vi vector<int>
#define pi pair<int, int>
#define fast ios_base::sync_with_stdio(false), cin.tie(nullptr), cout.tie(nullptr);
//goldminati
vector<vi> subsets;

void generateS(vector<int>&subset,int i, vector<int>nums){
// base condition

}

int32_t main(){
fast

int n;
cin>>n;
vi v(n);
for(int i = 0; i<n;i++){
   cin>>v[i];
}
vi nums;
generateS(v,0,nums);
for(auto a:valid){
    for(auto x:a){
        cout<<x<<" ";
    }
    cout<<"\n";
}



return 0;
}


```
