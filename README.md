#include<bits/stdc++.h>
using namespace std;
#define optimize() ios_base::sync_with_stdio(0);cin.tie(0);cout.tie(0);
#define en '\n'
#define ll long long int
#define pb push_back
#define vc vector
#define vi vc<int>
#define vl vc<ll>
#define mp(x,y) make_pair(x,y)
#define yes cout<<"YES"<<'\n';
#define no cout<<"NO"<<'\n';
#define tst int t;cin>>t;while(t--)
#define sort(v) sort(v.begin(),v.end())
#define r_sort(v) sort(v.rbegin(),v.rend())
#define rvs(v) reverse(v.begin(),v.end())
#define F first
#define S second
#define MOD 1000000007
#define gcd(a,b) __gcd(a,b)
#define lcm(a,b) (a*b)/gcd(a,b)
#define PI 2*acos(0.0)
#define pii pair<int,int>
#define fr(i,a,b) for(int i=a;i<=b;i++)
#define fr(j,a,b) for(int j=a;j<=b;j++)
#define coutv(v) for(auto it:v)cout<<it<<" ";cout<<endl;
#define cinv(v) for(auto &it:v)cin>>it;
#define all(v) v.begin(),v.end()
#define rall(v) v.rbegin(),v.rend()
#define uniq(v) int sz=unique(v.begin(),v.end())-v.begin()
#define for_string for(int i=0;i<s.size();i++)
/*
#include<bits/stdc++.h>
using namespace std;
#define optimize() ios_base::sync_with_stdio(0);cin.tie(0);cout.tie(0);
#define en '\n'
#define ll long long int
#define pb push_back
#define vc vector
#define vi vc<int>
#define vl vc<ll>
#define //mp(x,y) make_pair(x,y)
#define yes cout<<"YES"<<en
#define no cout<<"NO"<<en
#define tst int t;cin>>t;while(t--)
#define sort(v) sort(v.begin(),v.end())
#define rsort(v) sort(v.rbegin(),v.rend())
#define rvs(v) reverse(v.begin(),v.end())
#define F first
#define S second
#define MOD 1000000007
#define gcd(a,b) __gcd(a,b)
#define lcm(a,b) (a*b)/gcd(a,b)
#define PI 2*acos(0.0)
#define pii pair<int,int>
#define fr(i,a,b) for(int i=a;i<=b;i++)
#define fr(j,a,b) for(int j=a;j<=b;j++)
#define coutv(v) for(auto it:v)cout<<it<<" ";cout<<endl
#define cinv(v) for(auto &u:v)cin>>u
#define all(v) v.begin(),v.end()
#define rall(v) v.rbegin(),v.rend()
#define unique(v) int sz=unique(v.begin(),v.end())-v.begin()
#define for_string for(int i=0;i<s.size();i++)
///https://codeforces.com/problemset/problem/254/A
/*
void solve(int x,int y)
{


}

int main()
{
    optimize();
    tst
    {
        int x,y;
        cin>>x>>y;
        solve(x,y);
    }
}*/


///https://codeforces.com/contest/1589/problem/A  //////
   /* long long int t;
    cin>>t;
    while(t--){
        long long int a,b;
        cin>>a>>b;
        long long int y=b*b;
        long long int x=a*a;
        x=-x;
        cout<<x<<" "<<y<<endl;
    }

}*/
/*

    int t;
    cin>>t;
    while(t--)
    {
        int n;
        cin>>n;
        vector<int>v(n);
        for(int i=0;i<n;i++)
        {
            cin>>v[i];
        }
*/

    ///https://codeforces.com/contest/1177/problem/A
/*
////////////Codeforces Round 859 (Div. 4)////////https://codeforces.com/contest/1807/problem/B
    int x,b,m;
    cin>>x;
    while(x--){
        int t,b=0,m=0;;
        cin>>t;
        int ar[t];
        for(int i=0;i<t;i++) cin>>ar[i];
        for(int i=0;i<t;i++){
            if(ar[i]%2==0){
                m+=ar[i];
            }
            else{
                b+=ar[i];
            }
        }
       // cout<<m<<b;
        if(m>b) cout<<"YES"<<endl;
        else cout<<"NO"<<endl
    }*/
    ///https://codeforces.com/problemset/problem/1806/A
    /*
    int x,cnt;
    cin>>x;
    while(x--){
        int a,b,c,d;
        cnt=0;
        cin>>a>>b>>c>>d;
        while(a!=c || b!=d){
        if(b<d){
            a++;
            b++;
            cnt++;
         //   cout<<cnt<<" "<<a<<" "<<b<<endl;
            if(a==c && b==d) break;
        }

        else if(b==d && c<a){
            a--;
            cnt++;
          //  cout<<cnt<<" "<<a<<" "<<b<<endl;
            if(a==c && b==d) break;
        }

        else if(b==d && c>a) {
            cnt=-1;
            break;
        }
        }

        cout<<cnt<<endl;
    }

    }*/

    ///https://codeforces.com/contest/1798/problem/A
    /*
    int x,y,g,h;
    int temp;
    cin>>x;
    while(x--){
        cin>>y;
        vector<int>a(y);
        vector<int>b(y);
        for(int i=0;i<y;i++) cin>>a[i];
        for(int i=0;i<y;i++) cin>>b[i];


    for(int i=0;i<y;i++){
        temp=a[y-1-i];
        a[y-1-i]=b[y-1-i];
        b[y-1-i]=temp;
        for(int j=0;j<y;j++) cout<<a[j]<<" ";
        cout<<endl;
        for(int k=0;k<y;k++) cout<<b[k]<<" ";
        cout<<endl;
        cout<<endl;
        vector<int>:: iterator a_max=max_element(a.begin(),a.end());
        g=*a_max;

        vector<int>:: iterator b_max=max_element(b.begin(),b.end());
        h=*b_max;
        if(g==a[y-1] && h==b[y-1]) {
            cout<<"YES"<<endl;
           // cout<<g<<" "<<h<<endl;
            break;
        }

    }
        if(g!=a[y-1] || h!=b[y-1]){
            //cout<<g<<" "<<h<<endl;
           // cout<<a[y-1]<<" "<<b[y-1]<<endl;
            cout<<"NO"<<endl;
        }
    }
}
*/
///DAY-1
    ///1.https://codeforces.com/problemset/problem/71/A
    /*
    int x,c;
    cin>>x;
    while(x--){
        c=0;
        string s;
        cin>>s;
        int size_x=s.size();
        if(size_x<11) {
            cout<<s<<endl;
        }
        else{
            c=size_x-2;
            cout<<s[0]<<c<<s[size_x-1]<<endl;
        }
    }
}
*/
    ///2.https://codeforces.com/problemset/problem/231/A
    /*int x,p=0;
    cin>>x;
    while(x--){
        int a,b,c;
        cin>>a>>b>>c;
        int x=a+b+c;
        if(x==2 || x==3) p++;
    }
    cout<<p<<endl;
   }*/
   ///3.
   /*
    int x,y,r=0;
    cin>>x>>y;
    vector<int>v(x);
    for(int i=0;i<x;i++) cin>>v[i];
    for(int i=0;i<x;i++){
        if(v[i]>0){
            if(v[i]>=v[y-1]) r++;
        }

    }
    cout<<r<<endl;
}*/
    ///4.https://codeforces.com/problemset/problem/50/A
    /*
    int x,y,z;
    cin>>x>>y;
    z=x*y;
    int r=z/2;
    cout<<r<<endl;
}*/

    ///5.https://codeforces.com/problemset/problem/282/A
    /*
    int x;
    cin>>x;
    int c=0;
    while(x--){
        string s;
        cin>>s;
        if(s=="++X" || s== "X++") c++;
        else c--;
    }
    cout<<c<<endl;
}
*/
    ///6.https://codeforces.com/problemset/problem/263/A
    /*int x[5][5];
    int a,b;
    for(int i=0;i<5;i++){
        for(int j=0;j<5;j++){
            cin>>x[i][j];
        }
    }
    for(int i=0;i<5;i++){
        for(int j=0;j<5;j++){
            if(x[i][j]==1) {
                a=i;
                b=j;
            }
        }
    }
    int f1=abs(2-a);
    int f2=abs(2-b);
    cout<<f1+f2<<endl;
}
*/
    ///7.https://codeforces.com/problemset/problem/339/A
   /*
    string s,n,k;
    string c="+";
    cin>>s;
    for(int i=0;i<s.size();i++){
        if(s[i]=='1' || s[i]=='2' || s[i]=='3'){
            n+=s[i];
        }
    }
    sort(n.begin(),n.end());
    //cout<<n<<endl;
    for(int i=0;i<n.size();i++){
        k=n[i]+c;
        if(i==n.size()-1){
            k.pop_back();
        }
        cout<<k;
    }
    //cout<<k;

    //cout<<endl;
}*/
    ///9.https://codeforces.com/problemset/problem/281/A
   /*
    string s;
    cin>>s;
    char c=s[0];
    s.erase(s.begin());
    char u=toupper(c);
    string g=u+s;
    cout<<g;
}
*/
    ///10.https://codeforces.com/problemset/problem/236/A
    /*(string s;
    cin>>s;
    sort(s.begin(),s.end());
    int sz=unique(s.begin(),s.end())-s.begin();
    if(sz%2==0){
        cout<<"CHAT WITH HER!"<<endl;
    }
    else cout<<"IGNORE HIM!"<<endl;
}
*/
    ///11.https://codeforces.com/problemset/problem/266/A
    /*
    int x,c=0;
    cin>>x;
    string s;
    cin>>s;
    for(int i=0;i<x;i++){
        if(s[i]==s[i+1]) c++;
    }
    cout<<c<<endl;
}*/
    ///12.https://codeforces.com/problemset/problem/791/A
    /*
    int x,y,c=1;
    cin>>x>>y;
    while(x<=y){
        x*=3;
        y*=2;
        //cout<<x<<y<<endl;
        if(x<=y) c++;
    }
    cout<<c<<endl;
}*/
    ///13.https://codeforces.com/problemset/problem/546/A
    /*int x,y,z;
    int c=0;
    cin>>x>>y>>z;
    for(int i=1;i<=z;i++){
        c=c+(x*i);
    }
    if(c>y){
        int b=c-y;
        cout<<b<<endl;
    }
    else cout<<"0"<<endl;

}*/
    ///14.https://codeforces.com/problemset/problem/617/A
    /*int x;
    cin>>x;
    int c=0;
    if(x%5==0) c=x/5;
    else c=(x/5)+1;
    cout<<c<<endl;
}*/
    ///15.https://codeforces.com/problemset/problem/59/A
    /*
    string s;
    cin>>s;
    int l=0,u=0;
    for(int i=0;i<s.size();i++){
        if(s[i]>= 'a' && s[i]<= 'z') l++;
        else if(s[i]>= 'A' && s[i]<= 'Z') u++;
    }
    if(l>=u){
        for(int i=0;i<s.size();i++){
            char c=s[i];
            c=tolower(c);
            s[i]=c;
        }
        cout<<s;
    }
    else{
        for(int i=0;i<s.size();i++){
            char c=s[i];
            c=toupper(c);
            s[i]=c;
        }
        cout<<s;
    }
}*/

    ///16.https://codeforces.com/problemset/problem/977/A
    /*ll x;
    int y;
    cin>>x>>y;
    while(y--){
        if(x%10==0){
            x/=10;
        }
        else{
            x-=1;
        }
    }
    cout<<x<<endl;
}*/
    ///https://codeforces.com/contest/1808/problem/A

///TLE kysi
/*
int dif(int a){
    int b=0;
    while(a>0){
        b=(abs)(b-a%10);
        a/=10;
    }
    return b;
}

int main()
{
    optimize();
    int x;
    int index;
    cin>>x;
    for(int i=0;i<x;i++){
        int a,b;
        cin>>a>>b;
        int c=0;
        index=a;
        while(a<=b){
        int d=dif(a);
        if(d>=c){
            c=d;
            index=a;
            }
            a++;
        }
        cout<<index<<endl;
    }
}*/


    ///17.https://codeforces.com/problemset/problem/110/A
    /*string s;
    cin>>s;
    int c=0;
    for(int i=0;i<s.size();i++){
        if(s[i]=='4' || s[i]=='7') c++;

    }
    if(c==4 || c==7) cout<<"YES"<<endl;
    else cout<<"NO"<<endl;
}*/

    ///https://codeforces.com/problemset/problem/116/A
    /*
    int x;
    cin>>x;
    int ar[x][2];
    int p=0;
    for(int i=0;i<x;i++){
        for(int j=0;j<2;j++){
            cin>>ar[i][j];
        }
    }
    int max=0;
    for(int i=0;i<x;i++){
        for(int j=0;j<2;j++){
            if(j==0) {
                p-=ar[i][j];
            }
            else {
                p+=ar[i][j];
                if(p>max) max=p;
            }
        }
    }
    cout<<max<<endl;
}*/
    ///
    /*
    int x,c=0;
    cin>>x;
    while(x--){
        int y;
        cin>>y;
        vector<int>v(y);
        for(int i=0;i<y;i++) cin>>v[i];
        for(int i=0;i<y;i++){
            if(v[i]==i+1) {
                cout<<"YES"<<endl;
                c=1;
                break;
            }
        }
        if(c==0){
            cout<<"NO"<<endl;
        }

    }
}
*/

    ///https://codeforces.com/problemset/problem/266/B
    /*int x,y;
    cin>>x>>y;
    string s;
    cin>>s;
    for(int j=0;j<y;j++){
        for(int i=0;i<x-1;i++){
            if(s[i]=='B' && s[i+1]=='G'){
                s[i]='G';
                s[i+1]='B';
                i++;
            }
        }
    }
    cout<<s<<endl;
}*/
    ///https://codeforces.com/problemset/problem/677/A
    /*]
    int x,y;
    cin>>x>>y;
    int ar[x];
    int c=0;
    for(int i=0;i<x;i++) cin>>ar[i];
    for(int i=0;i<x;i++){
        if(ar[i]>y) c+=2;
        else c+=1;
    }
    cout<<c<<endl;
}

*/
    ///https://codeforces.com/problemset/problem/271/A
    /*
    int y;
    cin>>y;
    for(int i=y+1;;i++){
        string year= to_string (i);
        string s=year;
        int x=s.size();
        sort(s.begin(),s.end());
        int sz=unique(s.begin(),s.end())-s.begin();
        if(x==sz){
            cout<<i<<endl;
            return 0;
        }
    }
}
*/
    ///https://codeforces.com/problemset/problem/1030/A
    /*
    int x;
    cin>>x;
    int ar[x];
    for(int i=0;i<x;i++) cin>>ar[i];
    for(int i=0;i<x;i++){
        if(ar[i]==1){
            cout<<"HARD"<<endl;
            return 0;
        }
    }
    cout<<"EASY"<<endl;
}
*/
    ///https://codeforces.com/problemset/problem/467/A
    /*
    int x,cnt=0;
    cin>>x;
    for(int i=0;i<x;i++){
        int a,b;
        cin>>a>>b;
        int c=b-a;
        if(c>=2) cnt++;
    }
    cout<<cnt<<endl;
}*/
    ///https://codeforces.com/problemset/problem/136/A
    /*
    int x,c=1;
    cin>>x;
    int ar[x],nr[x];
    for(int i=0;i<x;i++) cin>>ar[i];
    for(int i=0;i<x;i++)
    {
        nr[ar[i]-1]=c;
        c++;
    }
    for(int i=0;i<x;i++) cout<<nr[i]<<" ";
    cout<<endl;
}
*/
    ///https://codeforces.com/problemset/problem/344/A
    /*
    int x,c=1;
    cin>>x;
    int ar[x];
    for(int i=0;i<x;i++) cin>>ar[i];
    for(int i=0;i<x-1;i++){
        if(ar[i]!=ar[i+1]) c++;
    }
    cout<<c<<endl;
}
*/
    ///https://codeforces.com/problemset/problem/486/A
    /*
    ll x,h;
    cin>>x;
    if(x%2==0)
    {
        h=(pow(-1,x)*x)/2;
        cout<<h<<endl;
    }
    else
    {
        x+=1;
        h=(pow(-1,x)*x)/2;
        h=(-1)*h;
        cout<<h<<endl;
    }

}
    int x;
    cin>>x;
    if(x!=15 && x<=25) cout<<"YES"<<endl;
    else cout<<"NO"<<endl;
}*/
    ///https://codeforces.com/contest/1805/problem/A
    /*
    int t,e=0;
    int sum;
    cin>>t;
    while(t--){
        int x;
        cin>>x;
        int ar[x];
        int br[x];
        for(int i=0;i<x;i++) cin>>ar[i];
        for(int j=1;j<256;j++){
            for(int i=0;i<x;i++){
                br[i]=ar[i]^j;
                if(i==0){
                    sum=br[0];
                }
                else if(i>0){
                    sum=sum^br[i];
                }
            }
        if(sum==0) {
            cout<<j<<endl;
            j=256;
            e=1;
            break;
        }
        sum=1;
        }
        if(e==0) cout<<"-1"<<endl;
        }

}
*/
    ///
/*
    int t;
    cin>>t;
    while(t--){
        int a,b;
        cin>>a>>b;Catalyst
        string bs=to_string(b);
        string s;
        cin>>s;
        char temp;
        string max1;
        s=bs+s;
        max1=s;
        for(int i=0;i<s.size()-1;i++){
                temp=s[i];
                s[i]=s[i+1];
                s[i+1]=temp;
                if(max1<s) max1=s;
            }
            cout<<max1<<en;

    }
}

*/
    ///https://codeforces.com/problemset/problem/200/B
   /*
    int a,sum=0;
    cin>>a;
    int ar[a];
    for(int i=0;i<a;i++) cin>>ar[i];
    for(int i=0;i<a;i++){
        sum+=ar[i];
    }
    double g=(double)(sum)/a;
   // double g=h/a;
    cout<<g<<en;
}
*/
    ///https://codeforces.com/problemset/problem/61/A
    /*
    string s1,s2;
    string s3;
    cin>>s1>>s2;
    for(int i=0;i<s1.size();i++){
        if(s1[i]!=s2[i]) s3+="1";
        else s3+="0";
    }
    cout<<s3<<en;
}
*/
    ///https://codeforces.com/problemset/problem/705/A
    /*
    int x;
    cin>>x;
    for(int i=1;i<=x;i++){
        if(i%2==1) {
            cout<<"I hate ";
            if(i==x) cout<<"it"<<en;
            else cout<<"that ";
        }
        else {
            cout<<"I love ";
            if(i==x) cout<<"it"<<en;
            else cout<<"that ";
        }
    }
}
*/
    ///https://codeforces.com/problemset/problem/228/A
    /*vector<int>v(4);
    for(int i=0;i<4;i++) cin>>v[i];
    sort(v.begin(),v.end());
    int z=unique(v.begin(),v.end())-v.begin();
    int a=4-z;
    cout<<a;
}

*/
    ///https://codeforces.com/problemset/problem/112/A
  /*  string s1,s2,s3;
    cin>>s1>>s2;
    transform(s2.begin(), s2.end(), s2.begin(), ::tolower);
    transform(s1.begin(), s1.end(), s1.begin(), ::tolower);
    if(s1>s2) cout<<"1"<<en;
    else if (s1<s2) cout<<"-1"<<en;
    else cout<<"0"<<en;
}
*/
/// https://codeforces.com/problemset/problem/469/A
    /*
    int x;
    cin>>x;
    int a;
    cin>>a;
    vector<int>v1(a);
    for(int i=0;i<a;i++) cin>>v1[i];
    int b;
    cin>>b;
    vector<int>v2(b);
    for(int i=0;i<b;i++) cin>>v2[i];
    v1.insert( v1.end(), v2.begin(), v2.end() );
    sort(v1.begin(), v1.end());
    int sz=unique(v1.begin(), v1.end())-v1.begin();
    if(sz==x) cout<<"I become the guy."<<en;
    else cout<<"Oh, my keyboard!"<<en;

}
*/
    ///https://codeforces.com/problemset/problem/144/A
    /*int x;
    cin>>x;
    int ar[x];
    int temp,index_max,index_min;
    for(int i=0;i<x;i++) cin>>ar[i];
    int max=0;
    int min=101;
    for(int i=0;i<x;i++)
    {
        if(max<ar[i])
           {
               max=ar[i];
               index_max=i;
           }

        if(min>=ar[i])
           {
               min=ar[i];
               index_min=i;
           }
    }
    //int time=()
    if(index_max>index_min){
        index_min++;
    }
    cout<<index_max+(x-1)-index_min<<en;
}
*/
    ///https://codeforces.com/problemset/problem/1328/A
    /*
    int x;
    cin>>x;
    while(x--){
        int a,b;
        cin>>a>>b;
        if(a%b==0) cout<<"0"<<en;
        else
        {int c=a/b;
        int d=b*(c+1)-a;
        cout<<d<<en;}
    }
}
*/
    ///https://codeforces.com/problemset/problem/148/A
    /*
    int e,sum=0;
    int ar[4];
    for(int i=0;i<4;i++) cin>>ar[i];
    cin>>e;
    vector<int>v;
    int m=e;
    for(int i=0;i<4;i++){
            for(int i=1;i<=e;i++){
                if(i%ar[0]==0 || i%ar[1]==0 || i%ar[2]==0 || i%ar[3]==0)
                {
                v.push_back(i);
                }
            }

    }
    sort(v.begin(),v.end());
    int sz=unique(v.begin(),v.end())-v.begin();
    cout<<sz<<en;
}
*/
    ///https://codeforces.com/problemset/problem/520/A
    /*\
    int x;
    cin>>x;
    string s2;
    cin>>s2;
    transform(s2.begin(), s2.end(), s2.begin(), ::tolower);
    sort(s2.begin(),s2.end());
    //int m=s2.size();
    int sz=unique(s2.begin(),s2.end())-s2.begin();
    if(sz==26) cout<<"YES"<<en;
    else cout<<"NO"<<en;
}

*/
    ///https://codeforces.com/problemset/problem/443/A
    /*
    string s2,s;
    getline(cin,s2);
    for(int i=0;i<s2.size();i++){
        if(s2[i]>='a' && s2[i]<='z'){
            s=s+s2[i];
        }
    }
    sort(s.begin(),s.end());
    int sz=unique(s.begin(),s.end())-s.begin();
    cout<<sz<<en;
}*/
    ///https://codeforces.com/problemset/problem/268/A
    /*int x,cnt=0;
    cin>>x;
    int ar[x],arr[x];
    for(int i=0;i<x;i++){
        cin>>ar[i];
        cin>>arr[i];
    }
    for(int i=0;i<x;i++){
        for(int j=0;j<x;j++){
                if(ar[i]==arr[j]){
                   cnt++;
                }
        }
    }
    cout<<cnt<<en;
}
*/
    ///https://codeforces.com/problemset/problem/996/A
/*
    int n;
    cin >> n;
    int count = 0;
    count += n / 100; // number of $100 bills
    n %= 100; // remaining balance
    count += n / 20; // number of $20 bills
    n %= 20; // remaining balance
    count += n / 10; // number of $10 bills
    n %= 10; // remaining balance
    count += n / 5; // number of $5 bills
    n %= 5; // remaining balance
    count += n; // number of $1 bills
    cout << count << endl;
}*/
    ///https://codeforces.com/problemset/problem/785/A
   /* int x,cnt=0;
    cin>>x;
    for(int i=0;i<x;i++){
        string s;
        cin>>s;
        if(s=="Tetrahedron") cnt+=4;
        else if(s=="Cube") cnt+=6;
        else if(s=="Octahedron") cnt+=8;
        else if(s=="Dodecahedron") cnt+=12;
        else if(s=="Icosahedron") cnt+=20;
    }
    cout<<cnt<<en;
}
*/
    ///https://codeforces.com/problemset/problem/141/A
    /*string s1,s2,s3;
    cin>>s1>>s2>>s3;
    string s=s1+s2;
    sort(s.begin(),s.end());
    sort(s3.begin(),s3.end());
    if(s==s3) cout<<"YES"<<en;
    else cout<<"NO"<<en;
}*/
    ///https://codeforces.com/problemset/problem/1335/A
    /*int t,cnt;
    cin>>t;
    while(t--){
        int x;
        cin>>x;
        int a,b;
        cnt=0;
        if(x>2){
        x=x-1;
        x=x/2;
            cout<<x<<en;
        }
        else cout<<"0"<<en;

    }
}*/
    ///https://codeforces.com/problemset/problem/510/A
    /*int x,y,cng=0;
    cin>>x>>y;
    for(int i=1;i<=x;i++){
        if(i%2!=0){
        for(int j=0;j<y;j++){
            cout<<"#";
        }
        cout<<en;
        }
        else{
            if(cng==0){
                for(int j=1;j<=y-1;j++){
                cout<<".";
                }
                cout<<"#"<<en;
                cng=1;
            }
            else{
                cout<<"#";
                for(int j=1;j<=y-1;j++){
                cout<<".";
                }
            cout<<en;
                cng=0;
            }
        }
    }
}*/
    ///https://codeforces.com/problemset/problem/427/A
    /*
    int x,p=0,cnt=0;
    cin>>x;
    for(int i=1;i<=x;i++){
        int a;
        cin>>a;
        if(a==-1){
            cnt++;
            if(p>0){
                p--;
                cnt--;
            }
        }
        else{
            p+=a;
        }
    }
    cout<<cnt<<en;
}
*/
    ///https://codeforces.com/contest/1814/problem/A
    /*int x;
    cin>>x;
    while(x--){
        ll n, k;
        cin >> n >> k;
        if(n % 2 == 0 || (n-k)%2==0 || k==1){
            cout << "YES\n";
        }
        else cout << "NO\n";
    }
}
*/

    ///https://codeforces.com/problemset/problem/556/A
    /*int x,c=0,d=0;
    cin>>x;
    string s;
    cin>>s;
    for(int i=0;i<x;i++){
        if(s[i]=='1') c++;
        else d++;
    }
    int t=abs(c-d);
    cout<<t;
}*/
    ///https://www.codechef.com/problems/ANDOR
    /*int t;
    cin>>t;
    while(t--){
        ll a;
        cin>>a;
        cout<<"0"<<" "<<a<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/155/A
    /*int x,c=0;
    cin>>x;
    int ar[x];
    for(int i=0;i<x;i++){
        cin>>ar[i];
    }
    int min=ar[0];
    int max=ar[0];
    for(int i=0;i<x;i++){
        if(ar[i]<min){
            min=ar[i];
            c++;
        }
        else if(ar[i]>max){
            max=ar[i];
            c++;
        }
    }
    cout<<c<<en;
}
*/
    ///https://codeforces.com/problemset/problem/750/A
    /*int x,y,m=0,c=0;
    cin>>x>>y;
    int v=240-y;
    for(int i=1;i<=x;i++){
        m=m+5*i;
        if(m<=v){
            c++;
        }
    }
    cout<<c<<en;
}*/
    ///https://codeforces.com/problemset/problem/1352/A
    ///********unsolved*******
  /*  int x,c=0;
    cin>>x;
    while(x--){
        int a;
        cin>>a;
        string s=to_string(a);
        int size=s.size();
        vector<int>v(size);
        for(int i=0;i<size;i++){
            string p=s[i];
            int l=stoi(p);
            int b=a*(pow(10,i));
            if(b!=0){
                v[i]=b;;
                c++;
            }
        }
        cout<<c<<en;
        for(int i=0;i<v.size();i++){
            cout<<v[i]<<" ";
        }
        cout<<en;
    }
*/
    ///https://codeforces.com/problemset/problem/581/A
    /*int x,y,c,min,max;
    cin>>x>>y;
    if(x>y){
        min=y;
        max=x;
        c=(max-min)/2;
        cout<<min<<" "<<c<<en;
    }
    else {
        min=x;
        max=y;
        c=(max-min)/2;
        cout<<min<<" "<<c<<en;
    }
    }*/
    ///https://codeforces.com/problemset/problem/732/A
    /*int x,y;
    cin>>x>>y;
    int c=1;
    for(int i=1;;i++){
        int j=x*i;
       //cout<<j<<en;
        int t=j%10;
        if(t==0){
            cout<<c<<en;
            return 0;
        }
        else{

            if(t/y==1 && t%y==0){
                cout<<c<<en;
                return 0;
            }
        }
        c++;
    }
}
*/
    ///https://codeforces.com/problemset/problem/723/A
    /*vector<int>v(3);
    for(int i=0;i<3;i++) cin>>v[i];
    auto mx=max_element(v.begin(),v.end());
    auto mi=min_element(v.begin(),v.end());
    cout<<*mx-*mi<<en;
}
*/
    ///https://codeforces.com/problemset/problem/1154/A
    /*vector<int>v(4);
    for(int i=0;i<4;i++) cin>>v[i];
    sort(v.begin(),v.end());
    int m1=v[1]-v[0];
    int m2=v[2];
    int c=(m1+m2)/2;
    int a=v[1]-c;
    int b=v[3]-(a+c);
    cout<<a<<" "<<b<<" "<<c<<" "<<en;
    }
*/
    ///https://codeforces.com/problemset/problem/1399/A
    /*int t;
    cin>>t;
    while(t--){
        int x;
        cin>>x;
        int c=0;
        vector<int>v(x);
        for(int i=0;i<x;i++) cin>>v[i];
        sort(v.begin(),v.end());
        for(int i=0;i<x-1;i++){
            int t=v[i+1]-v[i];
            if(t>1){
                c=1;
                break;
            }
        }
        if(c==0 || v.size()==1) cout<<"YES"<<en;
        else cout<<"NO"<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1409/A
    /*int t;
    cin>>t;
    while(t--){
        ll a,b;
        cin>>a>>b;
        if(a!=b){
            solve1(a,b);
        }
        else if(a==b) cout<<"0"<<en;
    }
}
void solve1(ll a,ll b){
    ll x=abs(a-b);
            ll m;
            if(x%10!=0) m=(x/10)+1;
            else m=(x/10);
            cout<<m<<en;
}*/
    ///https://codeforces.com/problemset/problem/151/A
    /*int ar[8];
    for(int i=0;i<8;i++) cin>>ar[i];
    vector<int>v(3);
    v[0]=(ar[1]*ar[2])/ar[6];
    v[1]=ar[3]*ar[4];
    v[2]=ar[5]/ar[7];
    auto mx=min_element(v.begin(),v.end());
    //auto mi=*mx;
    auto ans=*mx/ar[0];
    cout<<ans<<en;
}*/
    ///https://codeforces.com/problemset/problem/472/A
    /*int x;
    cin>>x;
    int a,b;
    a=4;
    b=x-4;
    while(a!=x){
        is_prime(a);
        is_prime(b);
        if(is_prime(a)==false && is_prime(b)==false){
            cout<<a<<" "<<b<<en;
            return 0;
        }
        a++;
        b--;
    }
}

bool is_prime(int a){
    for(int i=2;i<a;i++){
        if(a%i==0){
            return false;
        }
    }
     return true;
}*/
    ///https://codeforces.com/contest/1816/problem/A
    /*int x;
    cin>>x;
    while(x--){
        int a,b;
        cin>>a>>b;
        cout<<2<<en<<a-1<<" "<<"1"<<en<<a<<" "<<b<<en;
    }
}
*/
    ///https://codeforces.com/problemset/problem/432/A
    /*int x,y,c=0;
    cin>>x>>y;
    vector<int>v(x);
    for(int i=0;i<x;i++) cin>>v[i];
    sort(v.begin(),v.end());
    int r=v.size();
    while(v[r-1]>=5){
        v.pop_back();
        r=v.size();
    }
    if(v.size()<3) {
        cout<<"0"<<en;
        return 0;
        }

    else{
    for(int i=0;i<v.size();i+=3){
        if(v[i]+y<=5 && v[i+1]+y<=5 && v[i+2]+y<=5){
            c++;
        }
    }
    cout<<c<<en;
    }
}
*/



///https://codeforces.com/problemset/problem/734/A
  /*  int x;
    cin>>x;
    string s;
    cin>>s;
    int a=0,d=0;
    for(int i=0;i<x;i++){
        if(s[i]=='D') d++;
        else a++;
    }
    if(a>d) cout<<"Anton"<<endl;
    else if(d>a) cout<<"Danik"<<endl;
    else cout<<"Friendship"<<endl;
}
*/

    ///https://codeforces.com/problemset/problem/41/A
   /* string s,t,k;
    cin>>s>>t;
    reverse(s.begin(),s.end());
    if(s==t) cout<<"YES"<<endl;
    else cout<<"NO"<<endl;
}*/
    ///https://codeforces.com/problemset/problem/1367/A
    /*int t;
    cin>>t;
    while(t--){
        string s,s1;
        cin>>s;
        for(int i=1;i<s.size()-1;i++){
            s.erase(s.begin()+i);
        }
        cout<<s<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1512/A
    /*int t;
    cin>>t;
    while(t--){
        int n;
    cin >> n;
    vector<int> v(n);
    for (int &e : v) {
        cin >> e;
    }
    vector<int> a = v;
    sort(a.begin(), a.end());
    for (int i = 0; i < n; i++) {
        if (v[i] != a[1]) {
            cout << i + 1 << "\n";
        }
    }

    }
}

*/
    ///https://codeforces.com/problemset/problem/758/A
   /* int x,sum=0;
    cin>>x;
    vector<int>v(x);
    for(auto &u:v) cin>>u;
    auto mx=max_element(v.begin(),v.end());
    int max=*mx;
    for(int i=0;i<x;i++){
        int t=abs(v[i]-max);
        sum+=t;
    }
    cout<<sum<<en;
}
*/
    ///https://codeforces.com/problemset/problem/1343/B
    /*int t;
    cin>>t;
    while(t--){
        int x,sum=0,j=1,sum1=0;
        cin>>x;
        if(x%4==0){
            cout<<"YES"<<en;
            for(int i=2;i<=x;i+=2) {
                cout<<i<<" ";
                sum+=i;
            }
            int p=(x/2)-1;
            for(int i=1;i<=p;i++){
                cout<<j<<" ";
                sum1+=j;
                j+=2;
            }
            cout<<sum-sum1<<en;
        }
        else{
            cout<<"NO"<<en;
        }
    }
}
*/
    ///https://codeforces.com/problemset/problem/490/A
    /*int x,min=5001;
    cin>>x;
    vector<int>v(x);
    int ar[4]={0};
    for(auto &u:v) cin>>u;
    for(int i=0;i<x;i++){
        ar[v[i]]++;
    }
    for(int i=1;i<4;i++){
        if(ar[i]<min){
            min=ar[i];
        }
    }
    cout<<min<<en;
    int j=0,k=0,l=0,c=0;
    int indx1[5001];
    int indx2[5001];
    int indx3[5001];

        for(int i=0;i<x;i++){
            if(v[i]==1){
                indx1[j]=i+1;
                j++;
                v[i]=0;
            }
            else if(v[i]==2){
                indx2[k]=i+1;
                k++;
                v[i]=0;
            }
            if(v[i]==3){
                indx3[l]=i+1;
                l++;
                v[i]=0;
            }
        }
        for(int i=0;i<min;i++){
        cout<<indx1[i]<<" "<<indx2[i]<<" "<<indx3[i]<<en;
        }

}
*/
    ///https://codeforces.com/problemset/problem/381/A
    /*int x,j=0;
    cin>>x;
    vector<int>v(x);
    for(auto &u:v) cin>>u;
    int s=0,d=0;
    while(v.size()!=0){
        if(j==0){
            if(v[0]>v[v.size()-1]){
               s+=v[0];
               v.erase(v.begin());
               }
            else{
                s+=v[v.size()-1];
               v.pop_back();
               }
            j=1;
            }
        else{
           if(v[0]>v[v.size()-1]){
               d+=v[0];
               v.erase(v.begin());
               }
            else{
                d+=v[v.size()-1];
               v.pop_back();
               }
            j=0;
            }
    }
    cout<<s<<" "<<d<<en;
}
*/
///https://codeforces.com/contest/1793

    ///https://codeforces.com/problemset/problem/32/B
    /*string s;
    cin>>s;
    int t=s.size();
    for(int i=0;i<s.size();i++){
        if(s[i]=='-'){
            if(s[i+1]=='-') {
                cout<<2;
            i++;}
            else if(s[i+1]=='.') {
                    cout<<1;
            i++;}
        }
        else if(s[i]=='.'){
            cout<<0;
        }

    }
}
*/
    ///https://codeforces.com/problemset/problem/630/A
    /*int x;
    cin>>x;
    cout<<"25"<<en;
}*/
    ///https://codeforces.com/problemset/problem/1560/A
    /*int t,i,s;
    cin>>t;
    while(t--){
        int x,i=1;
        cin>>x;
        while(x--){
            if(i%3==0){
                i++;
                if(i%10==3){
                i++;
                }
            }
            if(i%10==3){
                i++;
                if(i%3==0){
                i++;
                }
            }
            s=i;
            i++;
        }
        cout<<s<<en;

    }
}
*/
    ///https://codeforces.com/problemset/problem/703/A]
    /*int t,m=0,c=0;
    cin>>t;
    while(t--){
        int a,b;
        cin>>a>>b;
        if(a>b){
            m++;
        }
        else if(a<b){
            c++;
        }
    }
    if(m>c) cout<<"Mishka"<<en;
    else if(m<c) cout<<"Chris"<<en;
    else cout<<"Friendship is magic!^^"<<en;
}
*/
    ///https://codeforces.com/problemset/problem/1703/A
   /* int x;
    cin>>x;
    while(x--)
    {
        string s;
        cin>>s;
        transform(s.begin(),s.end(),s.begin(), ::tolower);
        if(s=="yes") cout<<"YES"<<en;
        else cout<<"NO"<<en;
    }
}
*/
    ///https://codeforces.com/problemset/problem/1374/A
    ///solution deksi
    /*int t;
    cin>>t;
    while(t--){
        int x, y, n;
		cin >> x >> y >> n;
		if (n - n % x + y <= n) {
			cout << n - n % x + y << endl;
		} else {
			cout << n - n % x - (x - y) << endl;
		}
    }
}
*/

    ///https://codeforces.com/problemset/problem/1692/A
   /* int t,c;
    cin>>t;
    while(t--){
        c=0;
        vector<int>v(4);
        for(auto &u:v) cin>>u;
        for(int i=1;i<4;i++){
            if(v[0]<v[i]) c++;
        }
        cout<<c<<en;
    }
}
*/
    ///https://codeforces.com/problemset/problem/1742/A
    /*int t;
    cin>>t;
    while(t--){
        vector<int>v(3);
        for(auto &u:v) cin>>u;
        int max=*max_element(v.begin(),v.end());
        int sum=0;
        for(auto &u:v) sum+=u;
        if(sum==0) cout<<"YES"<<en;
        else{
        if(sum/max==2 && sum%max==0) cout<<"YES"<<en;
        else cout<<"NO"<<en;}
    }
}*/
    ///https://codeforces.com/problemset/problem/1520/A
    /*int t;
    cin>>t;
    while(t--){
        int x;
        cin>>x;
        string s,t,h;
        cin>>s;
            for(int i=0;i<s.size();i++){
                for(int j=i+1;j<s.size();){
                    if(s[i]==s[j]){
                        s.erase(s.begin()+j);
                    }
                    else break;
                }
            }
            t=s;
            sort(s.begin(),s.end());
            int sz=unique(s.begin(),s.end())-s.begin();
            if(t.size()==sz) cout<<"YES"<<en;
            else cout<<"NO"<<en;
        }
}
*/
    ///https://codeforces.com/problemset/problem/1624/A
    /*int t;
    cin>>t;
    while(t--){
        int x;
        cin>>x;
        vector<int>v(x);
        for(auto &u:v) cin>>u;
        int max=*max_element(v.begin(),v.end());
        int min=*min_element(v.begin(),v.end());
        cout<<max-min<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/431/A
    /*vector<int>v(4);
    for(auto &u:v) cin>>u;
    string s;
    cin>>s;
    int sum=0;
    for(int i=0;i<s.size();i++){
        if(s[i]=='1') sum+=v[0];
        else if(s[i]=='2') sum+=v[1];
        else if(s[i]=='3') sum+=v[2];
        else if(s[i]=='4') sum+=v[3];
    }
    cout<<sum<<en;
}
*/
    ///https://codeforces.com/problemset/problem/1353/B
    /*int t;
    cin>>t;
    while(t--){
        int x,k,sum=0;
        cin>>x>>k;
        vector<int>v1(x);
        vector<int>v2(x);
        for(auto &u:v1) cin>>u;
        for(auto &u:v2) cin>>u;
        sort(v1.begin(),v1.end());
        sort(v2.rbegin(),v2.rend());
        for(int i=0;i<k;i++){
            if(v1[i]<v2[i])  v1[i]=v2[i];
        }
        for(auto &u:v1) sum+=u;
        cout<<sum<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1360/A
    /*int t;
    cin>>t;
    while(t--){
        vector<int>v(2);
        for(auto &u:v) cin>>u;
        int min=*min_element(v.begin(),v.end());
        int max=*max_element(v.begin(),v.end());
        min=(2*min);
        if(max>min) cout<<pow(max,2)<<en;
        else cout<<pow(min,2)<<en;
    }
}
*/
    ///https://codeforces.com/contest/1821/problem/B

    ///RTE Kysi!!!!!!!!!!!!!

   /* int t;
    cin>>t;
    while(t--){
        int x,k=1;
        cin>>x;
        vector<int>v1(x);
        vector<int>v2(x);
        for(auto &u:v1) cin>>u;
        for(auto &u:v2) cin>>u;
        vector<int>t(x);
        t=v1;
        for(int i=0;i<x;i++){
            for(int j=0;j<x;j++){
                sort(v1.begin()+i,v1.end()-j);
                if(v2==v1){
                    cout<<i+1<<" "<<x-j<<en;
                    k=0;
                    break;
                }
                else v1=t;
            }
            if(k==0) break;
        }
    }
}
*/

    ///https://codeforces.com/problemset/problem/1433/A
    /*int t;
    cin>>t;
    while(t--){
        string s,t1;
        int temp=0;
        cin>>s;
        if(s=="1" && s.size()==1){
            cout<<1<<en;
        }
        else{
        t1=s;
        s.erase(s.begin()+1,s.end());
        //cout<<s<<en;
        int x=stoi(s);
        temp=(x-1)*10;
        for(int i=1;i<=t1.size();i++){
            temp+=i;
        }
        cout<<temp<<en;
        }
    }
}*/
    ///https://codeforces.com/problemset/problem/1676/A
/*int solve(string s1){
    string s3;
    int sum1=0;
    for(int i=0;i<s1.size();i++){
        s3+=s1[i];
        int k=stoi(s3);
        sum1+=k;
        s3.clear();
    }
    return sum1;
}

int main()
{
    int t;
    cin>>t;
    while(t--){
        string s,s1,s2;
        cin>>s;
        s1 = s.substr(0, s.size()-3);
        s2 = s.substr(s.size()-3);
        int sum1 = solve(s1);
        int sum2 = solve(s2);
        if(sum1==sum2) cout<<"YES\n";
        else cout<<"NO\n";
    }
    return 0;
}
*/
    ///https://codeforces.com/problemset/problem/9/A
    /*vector<int>v(2);
    for(auto &u:v) cin>>u;
    int max=*max_element(v.begin(),v.end());
    int c=6-(max-1);
    if(c==1) cout<<"1/6"<<en;
    else if (c==2) cout<<"1/3"<<en;
    else if (c==3) cout<<"1/2"<<en;
    else if (c==4) cout<<"2/3"<<en;
    else if (c==5) cout<<"5/6"<<en;
    else if (c==6) cout<<"1/1"<<en;
}*/
    ///https://codeforces.com/problemset/problem/1669/A
    /*int t;
    cin>>t;
    while(t--){
        int x;
        cin>>x;
        if(x<1400) cout<<"Division 4"<<en;
        else if(x>=1400 && x<1600) cout<<"Division 3"<<en;
        else if(x>=1600 && x<1900) cout<<"Division 2"<<en;
        else if(x>=1900) cout<<"Division 1"<<en;

    }
}*/
    ///https://codeforces.com/problemset/problem/1370/A
    /*int t;
    cin>>t;
    while(t--){
        int x;
        cin>>x;
        int max=x/2;
        cout<<max<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1811/A
    /*int t;
    cin>>t;
    while(t--){
        int x,c=0;
        string y;
        cin>>x>>y;
        string s,s1;
        cin>>s;
        for(int i=0;i<s.size();i++){
            if(s[i]<y[0] && c==0){
                s1+=y[0];
                c=1;
            }
            s1+=s[i];
        }
        if(s==s1) s1+=y;
        cout<<s1<<en;
    }
}
*/
    ///https://codeforces.com/problemset/problem/1810/B
    /*int t;
    string s,h;
    cin>>t;
    while(t--){
        s.clear();
        int n,k=0;
        cin>>n;
        if(n%2==0) cout<<"-1"<<en;
        else{
          vector<int>binaryNum(32);
          int i = 0;
          while (n > 0) {
          binaryNum[i] = n % 2;
          n = n / 2;
          i++;
          }
          cout<<i-1<<en;
          for (int j = i - 1; j > 0; j--) cout<<binaryNum[j]+1<<" ";
          cout<<en;
        }
    }
}*/
    ///https://codeforces.com/problemset/problem/1822/C
    /*int t;
    cin>>t;
    while(t--){
        ll x;
        cin>>x;
        ll temp=x*(x-3);
        ll ans=3+temp+(x-1)+4*x;
        cout<<ans<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1822/B
    /*int t;
    cin>>t;
    while(t--){
        int x;
        cin>>x;
        vector<ll>v(x);
        vector<ll>v1;
        for(auto &u:v) cin>>u;
        sort(v.rbegin(),v.rend());
        ll max=v[0]*v[1];
        auto transform = [](ll y) { return y >= 0 ? (-1)*y : (-1)*y; };
        std::transform(v.begin(), v.end(), v.begin(), transform);
        sort(v.rbegin(),v.rend());
        ll max1=v[0]*v[1];
        if(max<=max1) cout<<max1<<en;
        else cout<<max<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1822/A
    /*int t;
    cin>>t;
    while(t--){
        int x,y;
        cin>>x>>y;
        vector<int>v(x);
        for(auto &u:v) cin>>u;
        vector<int>v1(x);
        for(auto &u:v1) cin>>u;
        int max=0;
        int ans=-2;
        for(int i=0;i<x;i++){
            if(v[i]<=y-i){
                if(max<v1[i]){
                    max=v1[i];
                    ans=i;
                }
            }
        }
        cout<<ans+1<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1821/A
    /*int t;
    cin>>t;
    while(t--){
        string s;
        cin>>s;
        int ans=1;
        int c=0;
        if(s[0]=='?'){
            ans=9;
        }
        for(int i=1;i<s.size();i++){
            if(s[i]=='?') ans*=10;
        }
        if(s[0]=='0') cout<<"0"<<en;
        else cout<<ans<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1818/A
    /*int t;
    cin>>t;
    while(t--){
        int x,y;
        int c=1;
        cin>>x>>y;
        vector<string>v(x);
        for(auto &u:v) cin>>u;
        for(int i=1;i<x;i++){
            if(v[0]==v[i]) c++;
        }
        cout<<c<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1810/A
    /*int t;
    cin>>t;
    while(t--){
        int x,c=0;
        cin>>x;
        vector<int>v(x);
        for(auto &u:v) cin>>u;
        for(int i=0;i<x;i++){
            if(v[i]<=i+1){
                c=1;
                break;
            }
        }
        if(c==1) cout<<"YES"<<en;
        else cout<<"NO"<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1807/C
    /*int t;
    cin>>t;
    while(t--){
        int x,c=0;
        cin>>x;
        string s1,s2;
        cin>>s1;
        string s=s1;
        sort(s.begin(),s.end());
        int n=unique(s.begin(),s.end())-s.begin();
        s.erase(s.begin()+n,s.end());
        if(s1.size()==s.size()) cout<<"YES"<<en;
        else{
        int k=0;
        for(int i=0;i<s1.size();i++){
            for(int j=i+1;j<s1.size();j++){
                if(s1[i]==s1[j]){
                    if((i%2==0 && j%2!=0) || (i%2!=0 && j%2==0)){
                        cout<<"NO"<<en;
                        c=1;
                        i=s1.size();
                        j==s1.size();
                        break;
                    }
                }
            }
        }
        if(c==0) cout<<"YES"<<en;}
    }
}*/
    ///https://codeforces.com/problemset/problem/1807/B
    /*int x,b,m;
    cin>>x;
    while(x--){
        int t,b=0,m=0;;
        cin>>t;
        int ar[t];
        for(int i=0;i<t;i++) cin>>ar[i];
        for(int i=0;i<t;i++){
            if(ar[i]%2==0){
                m+=ar[i];
            }
            else{
                b+=ar[i];
            }
        }
        if(m>b) cout<<"YES"<<endl;
        else cout<<"NO"<<endl;
    }
}*/

    ///https://codeforces.com/contest/1806/problem/A
    /*int x,cnt;
    cin>>x;
    while(x--){
        int a,b,c,d;
        cin>>a>>b>>c>>d;
        int x1=d-b;
        int x2=(a+x1)-c;
        int ans=x1+x2;
        if(x1<0 || x2<0) cout<<"-1"<<en;
        else cout<<ans<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1805/B
    /*int t;
    cin>>t;
    while(t--){
        int x,c=0;
        cin>>x;
        string s,s1,s2;
        cin>>s;
        s1=s;
        sort(s.begin(),s.end());
        for(int i=s.size()-1;i>=0;i--){
            if(s1[i]==s[0]){
                s1.erase(s1.begin()+i);
                s2+=s[0];
                break;
            }
        }
        s2+=s1;
        cout<<s2<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1804/A
    /*int t;
    cin>>t;
    while(t--){
        int x,y;
        cin>>x>>y;
        if(abs(x)==abs(y)) cout<<2*abs(x)<<en;
        else {
            if(abs(x)>abs(y)) cout<<2*abs(x)-1<<en;
            else cout<<2*abs(y)-1<<en;
        }
    }
}*/
    ///https://codeforces.com/problemset/problem/1802/A
    /*int t;
    cin>>t;
    while(t--){
        int x,c=0,d=0,k=0;
        cin>>x;
        vector<int>v(x);
        for(auto &u:v) cin>>u;
        sort(v.rbegin(),v.rend());
        for(auto &u:v){
            if(u<0) cout<<--c<<" ";
            else cout<<++c<<" ";
        }
        cout<<en;
        for(auto &u:v){
            if(u<0) d++;
        }
        for(int i=1;i<=x;i++){
            if(d>0 && i%2==0){
                k--;
                d--;
                cout<<k<<" ";
            }
            else{
                k++;
                cout<<k<<" ";
            }
        }
        cout<<en;
    }
}*/
    ///https://codeforces.com/contest/1798/problem/A
    /*int t;
    cin>>t;
    while(t--){
        int x,c=0;
        cin>>x;
        vector<int>v1(x);
        vector<int>v2(x);
        for(auto &u:v1) cin>>u;
        for(auto &u:v2) cin>>u;
        int max1=*max_element(v1.begin(),v1.end());
        int max2=*max_element(v2.begin(),v2.end());
        for(int i=1;i<=x;i++){
            if(v1[x-i]>v2[x-i])
            swap(v1[x-i],v2[x-i]);
            int max1=*max_element(v1.begin(),v1.end());
            int max2=*max_element(v2.begin(),v2.end());
            if(max1==v1[x-1] && max2==v2[x-1]){
                cout<<"YES"<<en;
                c=1;
                break;
            }
        }
        if(c==0) cout<<"NO"<<en;
    }
}*/
    ///https://codeforces.com/problemset/problem/1797/A
    ///unsolved
    /*
    int t;
    cin>>t;
    while(t--){
        ll x,y,c=0,d=0;
        cin>>x>>y;
        vector<ll>v(4);
        for(auto &u:v) cin>>u;
        ll m=v[0]+v[1];
        ll n=v[2]+v[3];
        if(m==2 || (m==1+x && v[1]==x) || (m==1+y && v[1]==x || m==x+y || n==2 || n==1+x || n==1+y || n==x+y) cout<<"2"<<en;
        else if(v[0]!=1 && v[1]!=1 && v[0]!=x && v[1]!=y && v[2]!=1 && v[3]!=1 && v[2]!=x && v[3]!=y) cout<<"4"<<en;
        else cout<<"3"<<en;

    }
}*/
   /* int t;
    cin>>t;
    while(t--){
        int x,c=0;
        cin>>x;
        vector<int>v(x);
        for(auto &u:v) cin>>u;
        for(auto &u:v){
            if(u==x) c++;
        }
        if(c==x) cout<<"-1"<<en;
        else{
        int m=x-c;
        cout<<m<<en;

        }
    }
}
*/
    ///https://codeforces.com/contest/1829/problem/C
/*
    int t;
    cin>>t;
    while(t--){
        int x,d=0,sum1=0,k=0,l=0,m=0,sum2=2*(10^5),k1=0;
        cin>>x;
        vector<pair<int,string>>v(x);
        for(auto &u:v) cin>>u.first>>u.second;
        sort(v.begin(),v.end());
        for(auto &u:v){
            if(u.second=="10" && m==0) {
                d++;
                m=1;
                sum1+=u.first;
                if(d==2) k1=sum1;
            }
            else if(u.second=="01" && k==0){
                d++;
                k=1;
                sum1+=u.first;

                if(d==2) k1=sum1;
            }
            else if(u.second=="11" && l==0){
                d=2;
                l=1;
                sum2=u.first;
                break;
            }
        }
        if(d==2) {
            if(k1>sum2) cout<<sum2<<en;
            else if(k1<sum2 && k1!=0) cout<<k1<<en;
            else cout<<sum2<<en;
        }
        else cout<<"-1"<<en;

    }
}
*/

    ///https://codeforces.com/contest/1825/problem/A
    /*int t;
    cin>>t;
    while(t--){
        string s;
        int c=0;
        cin>>s;
        for(int i=0;i<s.size();i++){
            s.erase(s.begin()+i);
            string s1=s;
            reverse(s1.begin(),s1.end());
            if(s1!=s){
                c=1;
                break;

            }
        }
        if(c==0) cout<<"-1"<<en;
        else cout<<s.size()<<en;
    }
}*/
    ///https://codeforces.com/contest/1794/problem/A
    /*int t;
    cin>>t;
    while(t--){
        int x;
        cin>>x;
        string s;
        vector<string>v(2*x-2);
        for(auto &u:v) cin>>u;
        sort(v.begin(),v.end());
        for(auto &u:v){
            if(u.size()!=x-1) u.clear();
        }
        for(auto &u:v) s+=u;
        string k=s;
        s.erase(s.begin());
        s.pop_back();
        string tmp=s;
        reverse(s.begin(),s.end());
        if(k[0]==k[k.size()-1]){
            if(s==tmp) cout<<"YES"<<en;
            else cout<<"NO"<<en;
        }
        else cout<<"NO"<<en;

    }
}*/
    ///https://codeforces.com/contest/1796/problem/A
    /*int t;
    cin>>t;
    while(t--){
        int x;
        cin>>x;
        string s1;
        cin>>s1;
        string s3="BBF",s2="BBB";

        if(s1.find(s2) != std::string::npos) cout<<"NO"<<en;
        else if(s1.find(s3) != std::string::npos) cout<<"NO"<<en;
        else cout<<"YES"<<en;

    }
}*/
    ///https://codeforces.com/contest/1832/problem/0
    /*int x;
    cin>>x;
    while(x--){
    string s1;
    int c=0;
    cin>>s1;
    if(s1.size()%2!=0){
    int g=s1.size()/2;
    s1.erase(s1.begin()+g);}
    sort(s1.begin(),s1.end());
    int sz=unique(s1.begin(),s1.end())-s1.begin();
    if(sz!=1) cout<<"YES"<<en;
    else cout<<"NO"<<en;

    }
}
*/
    ///https://codeforces.com/contest/1823/problem/A
    /*tst{
        string s;
        cin>>s;
        int c=0;
        if(s[0]=='_') c++;
        if(s[s.size()-1]=='_') c++;
        if(s.size()==1 && s[0]=='^') c=1;
        if(s.size()==1 && s[0]=='_') c=2;

        for_string{
            if(s[i]=='_' && s[i]==s[i+1]) c++;
        }
        cout<<c<<en;
    }
}
*/
    ///https://codeforces.com/contest/1788/problem/A

    /*
void solve(vi v)
{

    int cnt=0;
    for(int i=0;i<v.size();i++){
        int multi1=0,multi2=0;
        for(int j=0;j<=i;j++){
            if(v[j]==2) multi1+=v[j];
        }
        for(int j=i+1;j<v.size();j++){
            if(v[j]==2) multi2+=v[j];
        }
        //cout<<multi1<<" "<<multi2<<en;
        if(multi1==multi2){
            cout<<i+1<<en;
            cnt=1;
            break;
        }

    }
    if(cnt==0) cout<<"-1"<<en;

}



int main()
{
    optimize();
    tst{
        int x;
        cin>>x;
        vi v(x);
        for(auto &u:v) cin>>u;
        solve(v);
    }
}
*/

    ///https://codeforces.com/contest/1786/problem/A1
/*

void solve(int x)
{
    int sum1=1,sum2=0,sumt=1,t=0, k=0;
    for(int i=2;sumt<x;i++){
        sumt+=i;
        if(t==0){
            if(sumt>x) sum2+=(i-(sumt-x));
            else sum2+=i;
            k++;
            if(k==2){
                t=1;
                k=0;
            }
        }
        else if(t==1){
            if(sumt>x) sum1+=(i-(sumt-x));
            else sum1+=i;
            k++;
            if(k==2){
                t=0;
                k=0;
            }
        }
    }
        cout<<sum1<<" "<<sum2<<en;
}


int main()
{
    optimize();
    tst{
        int x;
        cin>>x;
        solve(x);


    }
}

*/
    ///https://codeforces.com/contest/1778/problem/A
/*void solve(vi v)
{
    int sum=0;
    int ans=-1e9;
    for(auto &u:v) sum+=u;
    for(int i=0;i<v.size()-1;i++){
        if(v[i]==v[i+1]){
            if(v[i]==1) ans = max(ans, sum-4);
            else ans = max(ans, sum+4);
        }
        else {ans = max(ans, sum);}
    }
    cout<<ans<<en;
}


int main()
{
    optimize();
    tst{
        int x;
        cin>>x;
        vi v(x);
        for(auto &u:v) cin>>u;
        solve(v);
    }
}
*/
    ///https://codeforces.com/contest/1780/problem/A
/*
void solve(vi v)
{
    int even=0,odd=0,m=0,s=0;
    vi v_odd;
    vi v_even;
    for(int i=0;i<v.size();i++){
        if(v[i]%2==0){
            even++;
            v_even.push_back(i);
        }
        else{
            odd++;
            v_odd.push_back(i);
        }
    }
    if(odd>=3){
        yes;
        for(int i=0;i<3;i++){
            cout<<v_odd[i]+1<<" ";
        }
        cout<<en;
    }
    else if(odd<=2 && odd>0 && even>1){
        yes;
        for(int i=0;i<2;i++){
            cout<<v_even[i]+1<<" ";
        }
        for(int i=0;i<1;i++){
            cout<<v_odd[i]+1<<en;
        }
    }
    else no;


}


int main()
{
    optimize();
    tst{
        int x;
        cin>>x;
        vi v(x);
        for(auto &u:v) cin>>u;
        solve(v);
    }
}
*/

//https://codeforces.com/contest/1792/problem/A

/*
void solve(vi v)
{
    int sum=0,temp=0;
    vi v1=v;
    sort(v);
    unique(v);
    if(it==v.size()) cout<<v.size()<<en;
    else{
        map<int,int>fr;
        for(auto &u:v1) fr[u]++;
        for(auto &u:fr){
            if(u.first==1) temp=(u.second+1)/2;
            else sum+=u.second;
        }
        cout<<sum+temp<<en;
    }
}

int main()
{
    optimize();
    tst
    {
        int x;
        cin>>x;
        vi v(x);
        for(auto &u:v) cin>>u;
        solve(v);
    }
*/

///https://codeforces.com/contest/1777/problem/A
/*
void solve(vi v1)
{
    int c=0;
    for(int i=0;i<v1.size();i++)
    {
        if(v1[i]%2==0 && v1[i+1]%2==0) c++;
        else if(v1[i]%2!=0 && v1[i+1]%2!=0) c++;
    }
    cout<<c<<en;
}

int main()
{
    optimize();
    tst
    {
        int x;
        cin>>x;
        vi v(x);
        cinv(v);
        solve(v);
    }
}
*/
   ///https://codeforces.com/contest/1783/problem/A
/*
void solve(vi v)
{
    int c=0,temp;
    vi v1=v;
    sort(v);
    sort(v1);
    rvs(v1);
    unique(v);
    if(sz==1){
        cout<<"NO"<<en;
        c=1;
    }
    if(c==0){
        cout<<"YES"<<en;
        if(v1[0]==v1[1]){
            temp=v1[0];
            v1[0]=v1[v1.size()-1];
            v1[v1.size()-1]=temp;
        }
        coutv(v1);
    }
}

int main()
{
    optimize();
    tst
    {
        int x;
        cin>>x;
        vi v(x);
        cinv(v);
        solve(v);
    }
}
*/


///https://codeforces.com/contest/1731/problem/A
/*
   void solve(vi v)
{
    ll multi=1;
    for(auto &u:v) multi*=u;
    multi+=(v.size()-1);
    cout<<2022*multi<<en;
}

int main()
{
    optimize();
    tst
    {
        int x;
        cin>>x;
        vi v(x);
        cinv(v);
        solve(v);
    }
}
*/
///https://codeforces.com/contest/1731/problem/A
/*
void solve(string s)
{
    string s1;
    rvs(s);
    for(int i=s.size()-1;s.size()!=1;i--)
    {
        if(s[s.size()-1]=='1' && s[s.size()-2]=='1'){
            s.pop_back();
            s.pop_back();
            s+='0';
            s1+='-';
            //cout<<s<<en;
        }
        else if((s[s.size()-1]=='0' && s[s.size()-2]=='1') || (s[s.size()-1]=='1' && s[s.size()-2]=='0')){
            s.pop_back();
            s.pop_back();
            s+='1';
            s1+='+';
            //cout<<s<<en;
        }
        else if(s[s.size()-1]=='0' && s[s.size()-2]=='0'){
            s.pop_back();
            s.pop_back();
            s+='0';
            s1+='+';
            //cout<<s<<en;
        }
    }
    cout<<s1<<en;
}

int main()
{
    optimize();
    tst
    {
        int x;
        cin>>x;
        string s;
        cin>>s;
        solve(s);
    }
}
*/
///https://codeforces.com/contest/1833/problem/A
/*
void solve(string s)
{
    vector<string>v;
    string s1;
    for(int i=0;i<s.size()-1;i++){
        s1+=s[i];
        s1+=s[i+1];
        v.push_back(s1);
        s1.erase();
    }
    sort(v);
    unique(v);
    cout<<sz<<en;
}

int main()
{
    optimize();
    tst
    {
        int x;
        cin>>x;
        string s;
        cin>>s;
        solve(s);
    }
}
*/

///https://codeforces.com/contest/1833/problem/C
/*
void solve(vl v1)
{
    vl v2;
    vl v3;
    sort(v1);
    int e=0,o=0;
    for(auto &u:v1){
        if(u%2==0){
            v2.push_back(u);
            e++;}
        else {v3.push_back(u);
        o++;}
    }
    int min2=*min(v1.begin(),v1.end());
    if(e>o){
        if(min2%2==0 && o!=0) no;
        else yes;

    }
    else if(o>e){
        if(min2%2==0) no;
        else yes;
    }
    else if(e==o) {
        if(min2%2==0) no;
        else yes;
    }
}

int main()
{
    optimize();
    tst
    {
        int x;
        cin>>x;
        vl v(x);
        cinv(v);
        solve(v);

    }
}
*/




///https://codeforces.com/contest/1777/problem/A
///upsolved
/*
void solve(string s)
{
    int c=0;
    string s1,s2;
    for(int i=0;i<s.size();i++)
    {
        s1+=s[i];
        s2+=s[s.size()-i-1];
        s.erase(s.begin()+i);
        s.pop_back();
        if((s<=s1 && s<=s2) || (s>=s1 && s>=s2))
        {
            cout<<s1<<" "<<s<<" "<<s2<<en;
            c=1;
            break;
        }
    }
    if(c==0) cout<<":"<<en;
}

int main()
{
    optimize();
    tst
    {
        string s;
        cin>>s;
        solve(s);
    }
}
*/

///https://codeforces.com/contest/1829/problem/C
/*int main() {
    optimize();
    tst {
        int x, d = 0, sum1 = 0, k = 0, l = 0, m = 0, sum2 = 0, k1 = 0;
        cin >> x;
        vector<pair<string, int>> v(x),v1,v2,v3;
        for (auto &u : v) cin >> u.second >> u.first;
        sort(v);
        v1 = v;
        for (auto &u : v) {
            if (u.first == "10" && m == 0) {
                v2.push_back(u);
                m = 1;
            }
            else if (u.first == "01" && k == 0) {
                v2.push_back(u);
                k = 1;
            }
            else if (u.first == "11" && l == 0) {
                v3.push_back(u);
                l = 1;
            }
        }
        for (auto &u : v2) sum1+=u.second;
        for (auto &u : v3) k1=u.second;
        if(v2.size()<2 && v3.size()==1) cout<<k1<<en;
        else if(v3.size()==0 && v2.size()==2) cout<<sum1<<en;
        else if(v2.size()<2 && v3.size()==0) cout<<"-1"<<en;
        else if(v2.size()==2 && v3.size()==1){
            if(k1<sum1) cout<<k1<<en;
            else cout<<sum1<<en;
        }
    }
}
*/
///https://codeforces.com/contest/1818/problem/B
/*
void solve(int k)
{
    if(k==1) cout<<"1"<<en;
    else {
    vi v;
    int sum=(k*(k+1))/2;
    if(sum%k==0) cout<<"-1"<<en;
    else{
        for(int i=1;i<=k;i++) v.push_back(i);
        for(int i=0;i<v.size();i+=2){
            swap(v[i],v[i+1]);
        }
        coutv(v);

    }
    }

}

int main()
{
    optimize();
    tst
    {
        int x;
        cin>>x;
        solve(x);
    }
}
*/

///https://codeforces.com/contest/1808/problem/A
/*
void solve(int a,int b)
{
    string v;
    int ans=a;
    int maxif=0;
    for(int i=a;i<=b;i++){
        v=to_string(i);
        sort(v);
        int maxi=v[v.size()-1]-v[0];
        if(maxif<maxi){
            maxif=maxi;
            ans=i;
        }
        if(maxif==9) break;
    }
        cout<<ans<<en;

}

int main()
{
    optimize();
    tst
    {
        int x,y;
        cin>>x>>y;
        solve(x,y);
    }
}
 */
///https://codeforces.com/problemset/problem/1809/A
/*
void solve(string v)
{
    map<char,int>fr;
    vi s;
    for(auto &u:v) fr[u]++;
    for(auto &u:fr) s.push_back(u.second);
    if(s.size()==3) cout<<"4"<<en;
    else if(s.size()==4) cout<<"4"<<en;
    else if(s.size()==1) cout<<"-1"<<en;
    else if(s.size()==2){
        sort(s);
        unique(s);
        if(sz==1) cout<<"4"<<en;
        else cout<<"6"<<en;
    }

}

int main()
{
    optimize();
    tst
    {
        string s;
        cin>>s;
        solve(s);
    }
}
*/

///https://codeforces.com/contest/1833/problem/B
/*
void solve(int x,int y)
{
    vl v(x),v1(x);
    vector<pair<int,int>>p;
    for(int i=0;i<x;i++){
        cin>>v[i];
        p.push_back({v[i],i});
    }
    cinv(v1);
    sort(v1);
    sort(p);
    vl v2(x);
    for(int i=0;i<x;i++){
        v2[p[i].second]=v1[i];
    }
   for(auto &u :v2) cout<<u<<" ";
   cout<<en;
}

int main()
{
    optimize();
    tst
    {
        int x,y;
        cin>>x>>y;
        solve(x,y);
    }
}
*/\
///https://codeforces.com/problemset/problem/254/A
///TLE
/*

void solve(vi v)
{
    int h;
    vi v1;
    map<int,int>fr;
    for(auto &u:v) fr[u]++;
    for(auto &u:fr){
        if(u.second>1) u.second%=2;
        v1.push_back(u.second);
    }
    int k=0;
    sort(v1);
    unique(v1);
    if(sz==1 && v1[0]==1) cout<<"-1"<<en;
    else if(sz!=1) cout<<"-1"<<en;
    else{
        for(auto &u:fr){
            for(int i=0;i<v.size();i++)
            {
                if(u.first==v[i] && k<2)
                {   cout<<i+1<<" ";
                    k++;
                    if(k==2){
                        cout<<en;
                        k=0;
                    }
                }
            }
        }
    }
}

int main()
{
    optimize();

    int x;
    cin>>x;
    vi v(2*x);
    cinv(v);
    solve(v);
}

*/

///https://codeforces.com/problemset/problem/1829/D
/*
void solve(int a,int y)
{
    vi v;
    int k=0;
    v.push_back(a);
    for(int i=0;i<v.size();i++){
        if(v[i]%3==0){
            v.push_back(v[i]/3);
            v.push_back((v[i]/3)*2);
        }
    }
    sort(v);
    for(auto &u:v) if(u==y){
        yes;
        k=1;
        break;
    }
    if(k==0) no;

}

int main()
{
    optimize();
    tst
    {
        int x,y;
        cin>>x>>y;
        solve(x,y);
    }
}
*/
///https://codeforces.com/problemset/problem/1823/B
/*
void solve(vi v,int y)
{
    vi v1;
    int c=0;
    for(int i=0;i<v.size();i++){
        v1.push_back(abs(v[i]-i-1));
    }
    for(int i=0;i<v.size();i++){
        if(v1[i]%y!=0) c++;
    }
    if(c==0) cout<<"0"<<en;
    else if(c==2) cout<<"1"<<en;
    else cout<<"-1"<<en;

}

int main()
{
    optimize();
    tst
    {
        int x,y;
        cin>>x>>y;
        vi v(x);
        cinv(v);
        solve(v,y);
    }
}
*/
///https://dmoj.ca/problem/ccc10s1
/*
int main()
{
    optimize();
    int x;
    cin>>x;
    int sum;
    if(x==0) cout<<en;
    else if(x==1){
        string s;
        int a,b,c;
        cin>>s>>a>>b>>c;
        cout<<s<<en;
    }
    else{
    vector<pair<int,string>>p(x);
    for(int i=0;i<x;i++){
        string s;
        ll a,b,c;
        cin>>s>>a>>b>>c;
        sum=-(2*a+3*b+c);
        p[i]=make_pair(sum,s);
    }
    sort(p.begin(),p.end());
    cout<<p[0].second<<en;
    cout<<p[1].second<<en;
    }
}
*/
///https://codeforces.com/contest/1816/problem/B
/*
void solve(int x)
{
    vi v1;
    vi v2;
    for(int i=0;i<x;i++){
        if((i+1)%2!=0){
            v1.push_back(2*x-i);
            v2.push_back(i+1);
        }
        else{
            v1.push_back(i+1);
            v2.push_back(2*x-i);
        }
    }
    swap(v2[1],v2[v2.size()-1]);
    coutv(v1);
    coutv(v2);

}
int main()
{
    optimize();
    tst
    {
       int x;
       cin>>x;
       solve(x);
    }
}
*/
///https://codeforces.com/contest/1807/problem/D
///upsolved...........
///prefix sum.
/*
void solve(int x,int y)
{
    vl v1(x);
    cinv(v1);
    vector<int>pre(x+5, 0);
    pre[0]=0;
    for(int i=1; i<=x; i++) pre[i] = pre[i-1] + v1[i];
    for(int i=0; i<y; i++) {
        int l, r, k; cin >> l >> r >> k;
        int subsum = pre[r]-pre[l-1];
        int sum = pre[x]-subsum+(r-l+1)*k;
        if(sum%2!=0) yes;
        else no;
    }


}
int main()
{
    optimize();
    tst
    {
       int x,y;
       cin>>x>>y;
       solve(x,y);
    }
}*/

///https://codeforces.com/contest/1805/problem/A
/*
void solve(vi v)
{
    vi v1;
    int c=0;
    int g,t;
    for(int j=0;j<256;j++){
        for(int i=0;i<v.size();i++){
            g=v[i]^j;
            v1.push_back(g);
        }
        t=v1[0];
        for(int i=1;i<v1.size();i++){
            t^=v1[i];
        }
        if(t==0) {
            cout<<j<<en;
            c=1;
            break;
        }
        v1.clear();
    }
    if(c==0) cout<<"-1"<<en;
}
int main()
{
    optimize();
    tst
    {
       int x;
       cin>>x;
       vi v(x);
       cinv(v);
       solve(v);
    }
}
*/
///https://codeforces.com/contest/1811/problem/B
/*
void solve(vl v)
{
    ll min1=min(min(v[1],v[0]-v[1]+1),min(v[2],v[0]-v[2]+1));
    ll min2=min(min(v[3],v[0]-v[3]+1),min(v[4],v[0]-v[4]+1));
    cout<<abs(min1-min2)<<en;
}
int main()
{
    optimize();
    tst
    {
       vl v(5);
       cinv(v);
       solve(v);
    }
}
*/
///https://codeforces.com/contest/1806/problem/B
/*
void solve(vi v,int x)
{
    int z=0,nz=0;
    for(auto &u:v){
        if(u==0) z++;
        else nz++;
    }
    if(z==0) cout<<"0"<<en;
    else{
        if(z-1<=nz) cout<<"0"<<en;
        else{
            max(v);
            if(mx==1) cout<<"2"<<en;
            else cout<<"1"<<en;
        }
    }
}
int main()
{
    optimize();
    tst
    {
       int x;
       cin>>x;
       vi v(x);
       cinv(v);
       solve(v,x);
    }
}
*/
///https://codeforces.com/contest/1837/problem/B
/*
void solve(string s)
{
    int c1=0,c2=0,max1=0,max2=0;
    fori(i,0,s.size()){
        if(s[i]=='<'){
            c1++;
            max1=max(max1,c1);
            c2=0;
        }
        else if(s[i]=='>'){
            c2++;
            max2=max(max2,c2);
            c1=0;
        }
    }
    int ans=max(max1,max2)+1;
    cout<<ans<<en;
}
int main()
{
    optimize();
    tst
    {
       int x;
       cin>>x;
       string s;
       cin>>s;
       solve(s);
    }
}
*/
///https://codeforces.com/contest/1837/problem/C
/*

void solve(string s)
{
    string s1;
    if(s[0]=='?') s[0]='0';
    for(int i=1;i<s.size();i++){
        if(s[i]=='?') s[i]=s[i-1];
    }cout<<s<<en;
}
int main()
{
    optimize();
    tst
    {
       string s;
       cin>>s;
       solve(s);
    }
}
*/
///https://leetcode.com/problems/maximum-strength-of-a-group/
/*
long long int solve(vector<int>v)
{
    int c=0,k=0;
    long long int multi=1,multi1=1;
    vector<int>v1;
    if(v.size()==1) return v[0];
    for(int i=0;i<v.size();i++){
            multi1*=v[i];
        }
    for(int i=0;i<v.size();i++){
        if(v[i]<0){
            c++;
        }
    }
    sort(v.begin(),v.end());
    if(c%2==0){
        for(int i=0;i<v.size();i++){
            if(v[i]!=0){
                multi*=v[i];
                k=1;}
        }
    }
    else{
        c--;
        v.erase(v.begin()+c);
        for(int i=0;i<v.size();i++){
            if(v[i]!=0) {
                multi*=v[i];
                k=1;}
        }
    }
    if(k==0) multi=-1;
    return max(multi,multi1);
}
int main()
{
    optimize();
    tst
    {
       vector<int>v;
       cinv(v);
       solve(v);
    }
}
*/
///https://codeforces.com/contest/1795/problem/A
/*
bool solve(string s1,string s2)
{
    int c1=1,c2=1;
    for(int i=0;i<s1.size();i++){
        if(s1[i]==s1[i+1]) c1++;
    }
    for(int i=0,j=0;i<s1.size(),j<s2.size();i++,j++){
        if(s2[j]==s2[j+1]) c2++;
    }
    if(c1==1 && c2==1) return true;
    else if(c1>1 && c2>1) return false;
    else if(((c1==2 && c2==1) || (c1==1 && c2==2)) && (s1[s1.size()-1]!=s2[s2.size()-1])) return true;
    else return false;

}
int main()
{
    optimize();
    tst
    {
       int x,y;
       cin>>x>>y;
       string s1,s2;
       cin>>s1>>s2;
       bool ans=solve(s1,s2);
       if(ans) yes;
       else no;
    }
}
*/

///https://codeforces.com/contest/1804/problem/B
/*
void solve(vi v,int k,int d,int w)
{
    int ans=0;
    int vx,r=k;
    for(int i=0;i<v.size();i++){
        if(i==0 || r==0 || vx<v[i]){
            ans++;
            vx=v[i]+w+d;
            r=k;
        }
        r--;
    }
    cout<<ans<<en;
    //coutv(v1);
}
int main()
{
    optimize();
    tst
    {
       int x,k,d,w;
       cin>>x>>k>>d>>w;
       vi v(x);
       cinv(v);
       solve(v,k,d,w);
    }
}

///https://codeforces.com/contest/1825/problem/B
/*
void solve(vi v,int x,int y)
{
    sort(v);
    int t,g;
    g=x*y;
    t=min(x,y);
    ll m1=((v[v.size()-1]-v[0])*(g-t))+((v[v.size()-1]-v[1])*(t-1));
    ll m2=((v[v.size()-1]-v[0])*(g-t))+((v[v.size()-2]-v[0])*(t-1));
    cout<<max(m2,m1)<<en;
}
int main()
{
    optimize();
    tst
    {
       int x,y;
       cin>>x>>y;
       vi v(x*y);
       cinv(v);
       solve(v,x,y);
    }
}
*/
///https://codeforces.com/contest/1789/problem/A
/*
void solve(vi v)
{
    sort(v);
    int k;
    for(int i=0;i<v.size()-1;i++){
        for(int j=i+1;j<v.size();j++){
            k=gcd(v[i],v[j]);
            if(k<=2){
                c=1;
            }
        }
    }
    if(c==1) yes;
    else no;
}
int main()
{
    optimize();
    tst
    {
       int x;
       cin>>x;
       vi v(x);
       cinv(v);
       solve(v);
    }
}
///https://codeforces.com/contest/1821/problem/B
/*
void solve(vi v,vi v1,int x)
{
    int e=v.size();
    int s=0,k=0;
    vi v3=v;
    sortv(v3);
    for(int i=0;i<v.size();i++){
        if(v[i]!=v1[i] ){
            if(k==0){
                s=i;
                k=1;
            }
            else if(k==1){
                e=i;
            }
        }
    }
    for(int i=s;i>=1;i--){
        if(v1[i-1]==v[i-1] && v1[i-1]<=v1[i]) s--;
        else break;
    }
    for(int j=e;j<v.size()-1;j++){
        if(v1[j+1]==v[j+1] && v1[j+1]>=v1[j]) e++;
        else break;
    }
    cout<<s+1<<" "<<e+1<<en;

}
int main()
{
    optimize();
    tst{
       int x;
       cin>>x;
       vi v(x);
       vi v1(x);
       cinv(v);
       cinv(v1);
       solve(v,v1,x);
    }
}
*/
///https://codeforces.com/contest/451/problem/B
/*
void solve(vl v,int x)
{
    vl v2=v;
    sortv(v2);
    vl v3,v4;
    ll c=0,k=0,s,e;
    vector<pair<int,int>>p(x);
    if(v==v2){
        cout<<"yes"<<en;
        cout<<"1"<<" "<<"1"<<en;
    }
    else{
        for(int i=0;i<v.size();i++){
            p[i]=make_pair(v[i],i);
        }
        sortv(p);
        for(int i=0;i<v.size();i++){
            v4.push_back(p[i].second);
        }
        for(int i=0;i<v.size();i++){
            if(i!=v4[i]){
                if(k==0){
                    s=i;
                    k=1;
                }
                else if(k==1){
                    e=i;
                }
            }
        }
        reverse(v.begin()+s,v.begin()+e+1);
        if(v==v2){
            cout<<"yes"<<en;
            cout<<s+1<<" "<<e+1<<en;
        }
        else cout<<"no"<<en;
    }



}
int main()
{
    optimize();
    //tst{
       int x,y;
       cin>>x;
       vl v(x);
       cinv(v);
       solve(v,x);
    //}
}
*/

























