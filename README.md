# roots
#include <iostream>
using namespace std;
int main() {
    int a,b,c,d;
    cout<<"a,b,c:";
    cin>>a>>b>>c;
    d=b*b-4*a*c;
    if(d<0)
    cout<<"imaginary";
    else if(d>0)
    cout<<"real";
    else
    cout<<"perfect";
    return 0;
}
