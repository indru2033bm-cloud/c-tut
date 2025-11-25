# c-tut
tut39
#include<iostream>
using namespace std;
class Base{
  protected:
  int a;
  private:
  int b;
};
class Derived : protected Base{

};
int main(){
    Base b;
    Derived c;
    // cout<<d.a;//will not work since a is protected in both base as weii as derived class
return 0;
}
