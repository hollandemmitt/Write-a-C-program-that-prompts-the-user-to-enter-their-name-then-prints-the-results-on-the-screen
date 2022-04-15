# Write-a-C-program-that-prompts-the-user-to-enter-their-name-then-prints-the-results-on-the-screen
Write a C++ program that prompts the user to enter their name, then prints the results on the screen
#include <cstdlib>
#include <iostream>
  
using namespace std;
int main(int argc, char *argv[])
{
     char name[20];
     cout<<"Or enter your name:";
     cin>>name;
     cout<<"Hello "<<name<<"! \n";
        
     return 0;
}
