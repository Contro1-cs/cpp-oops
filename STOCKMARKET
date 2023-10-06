//https://www.codechef.com/problems/STOCKMARKET

#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int t;cin>>t;
	while(t--){
	    int n;cin>>n;
	    int arr[n];
	    int sum=0, min = 10000;
	    for(int i=0;i<n;i++){
	        cin>>arr[i];
	        if(arr[i]<min){
	            min = arr[i];
	        }
	        sum+=arr[i];
	    }
	    cout<<sum-min<<endl;
	}
	return 0;
}
