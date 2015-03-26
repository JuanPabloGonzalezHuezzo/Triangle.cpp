# Triangle.cpp
#include <iostream>
using namespace std;
  void triangle(int n) {
      for (int a=1; a<=n; a++){
        for (int b=1; b<=a; b++){
          cout << "t";
        }
        cout << endl;
      }
      for (int c=n-1; c>=0; c--){
          for (int d=1; d<=c; d++){
              cout << "t";
          }
          cout << endl;
      }
      // should we use "return;" in here?
  }
int main(){
  int x;
  cout << "Haremos un triangulo con la letra 't' por usted, de que tamaño quiere que lo hagamos? " << endl;
  cin >> x;
  cout << endl;
  triangle(x);
}
