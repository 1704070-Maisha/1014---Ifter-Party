# 1014---Ifter-Party
#include<bits/stdc++.h>
using namespace std;
typedef unsigned long  ll;
 
vector<ll>vc;
void cal(ll p)
{
    ll a;
   // vector<ll>vc;
       vc.clear();
        for(ll j=1;j<=sqrt(p);j++)
        {
            if(p%j==0)
            {
              a=p/j;
              vc.push_back(j) ;
              if(a!=j)
              vc.push_back(a) ;
            }
        }
 
}
int main()
{
 
  ll t,n,m,p,b;
  //cin>>t;
  scanf("%lu",&t);
  for(ll k=1;k<=t;k++)
  {
     // cin>>n>>m;
       scanf("%lu %lu",&n,&m);
      p=n-m;
      cal(p);
      vector<ll>vt;
      for(ll i=0;i<vc.size();i++)
      {
          b=vc[i];
          if(n%b==m)
            vt.push_back(b);
      }
      //cout<<"Case "<<k<<": ";
       printf("Case %lu: ",k);
      if(vt.size()==0)
        printf("impossible\n");
    else
     {
        sort(vt.begin(),vt.end());
        for(ll i=0;i<vt.size();i++){
             printf("%lu",vt[i]);
             if(i<vt.size()-1)
             printf(" ");
        }
           // cout<<vt[i]<<" " ;
        printf("\n");
     }
     vt.clear();
     vc.clear();
   }
}
 
