# eureca-solution
#include <iostream>
#include <bits/stdc++.h>
using namespace std;

int main()
{
    int t;
    cin>>t;
    for(int i=0;i<t;i++){
        int n;
        cin>>n;
         float c =((0.143)*n);
         float d=pow(c,n);
        // cout<<(d)<<"\n";
         int f=(int)d;
         float r=d-f;
     //    cout<<f<<"\n"<<r;
         if(r<0.5){
            cout<<f<<"\n";
         }else{
         cout<<f+1<<"\n";
         }
    }
}
