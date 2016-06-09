#include <iostream>
#include <string>
int main ()
{
  string name;
  cout << "Enter your full name: ";
  getline (cin, name);
  cout << "Welcome to github " << name << " !" << endl;
  
  return 0;
}
