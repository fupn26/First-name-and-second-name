# First-name-and-second-name
#include "std_lib_facilities.h"
int main()
{
cout<<"Please enter your first and second names\n";
string first;
string second;
cin>> first >> second;
cout<<"Hello,"<<first<<" "<<second<<'\n';
}

# Another way to print you full name on the screen
#include "std_lib_facilities.h"
int main()
{
cout<< "Please enter your first an second names!\n";
string first;
string second;
cin>> first >> second;
string name = first+" "+second; #Here we make another variable and its value is the combination of the first and the second 
cout<< "Hello, "<<name<<"!\n";
}
