# Afford-
Coding Problem -1

#include<iostream>
#include<cstring>
  using namespace std;
  
  int main() {
  int chunk;
  char bytes[100];
  cin>>chunk;
  cin>>bytes;
  
  int l= strlen(bytes);
  int ans = chunk + l;
  cout<<ans;
  
  }
  
  
  
  
Coding Problem - 2
  
#include<iostream>
#include<cstring>
using namespace std;
  


int main() {
  
  string str;
  cin>>str;
  int f[256] = {0};
  
  string a="";
  
  for(int i=0; i<str.length(); i++){
      f[str[i]]++;
  }
  
  for(int i=0; i<256; i++){
      if(f[i] > 0)
      {
         a += i;
      }
  }
  
  
  cout<<a;

}
  
