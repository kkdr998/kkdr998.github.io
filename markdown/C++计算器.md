#include <bits/stdc++.h> 
using namespace std;
int main(){
	long long a,c;
    char b;
    cin>>a>>b>>c;
    switch(b){
    	case '+':cout<<a+c;break;
    	case '-':cout<<a-c;break;
    	case '*':cout<<a*c;break;
    	case '/':cout<<a/c;break;
    	case '%':cout<<a%c;break;
    	default:cout<<"Error";break;
		}
}
