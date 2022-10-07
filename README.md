#include<iostream>
  using namespace std;
  int main (){
  float a, b,c;
  cout<<"calculate ur bmi \n ";
   cout<<"enter ur weight and height repectively\n";
  cin>>a>>b;
  
  c=a/b/b;
  if(c<18.5){
              cout<<"underweight";
                     }
   if(c>=25 ){
  cout<<"overweight";
  }
  else{
  cout<<"normal";
  }
  return 0;
  }
  
