#include<iostream>
#include<math.h>
using namespace std;
int perkalian,pembagian,nilai1,nilai2;
string simbol;

int kali(int nilai,int nilai2){
int kalikan;
  kalikan = nilai1*nilai2;
return kalikan;
}

int bagi(int nilai1,int nilai2){
int bagikan;
bagikan = nilai1/nilai2;
return bagikan;
}

int main()
  cout<<"masukkan angka pertama :";
  cin>>nilai1;
  cout<<endl;
  cout<<"angka kedua : ";
  cin>>nilai2;
  cout<<endl;
  
  perkalian = kali(nilai1, nilai2);
  pembagian = bagi(nilai1, nilai2);
  
  cout<<"masukkan simbol :";
  cin>>simbol;
  cout<<endl;
  
  if(simbol=="*"){
    cout<<"hasil kali"<<nilai1<<simbol<<nilai2<<" :  "<<perkalian<,endl;
  }
  else if(simbol=="/"){
    cout<<hasil bagi"<<nilai1<<simbol<<nilai2<<" : "<<pembagian<<endl;
  }
  return 0;
}

