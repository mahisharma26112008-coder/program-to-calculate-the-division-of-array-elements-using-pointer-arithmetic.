# program-to-calculate-the-division-of-array-elements-using-pointer-arithmetic.

#include<iostream> 
#include<iomanip>
  using namespace std;
   int main(){
       int arr[]={10,20,30,40,50};
       int *p=arr;
    float div=*p;

       for(int i=1;i<5;i++){
           div=div / *(p+i);
       }

       cout<<fixed<< setprecision(10);
       cout<<"division of elements : "<<div;

       return 0;
   }
