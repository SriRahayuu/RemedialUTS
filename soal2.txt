#include<iostream>
#include<string.h>
using namespace std;
int main()
{
  struct mahasiswa
  {
    char nama[50];
    char nim[15];
    char ipk[9];
  }a,b;
  
  strcpy(a.nama,"ajis gagap");
  strcpy(a.nim,"102904049");
  strcpy(a.ipk,"2,5");
  
  cout<<"nama :"<<a.nama<<endl;
  cout<<"nim :"<<a.nim<<endl;
  cout<<"ipk :"<<a.nim<<endl;
  cout<<endl;
  
  strcpy(b.nama,"tuming");
  strcpy(b.nim,"102904050");
  strcpy(b.ipk,"3,0");
  
  cout<<"nama :"<<b.nama<<endl;
  cout<<nim :"<<b.nim<<endl;
  cout<<ipk :<<b.ipk<<endl;
  
  return 0;
}
