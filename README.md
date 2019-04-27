 #include <iostream>
using namespace std;


int main ()
{
char str[50]; //user input
here:std::cin.getline(str,50);
if(strcasecmp ("hello", str)==0)//if both are same{
cout<<"Hello, what's your name"<<endl;
goto here;
}
else if(! strcasecmp ("hi" str)) {
cout<<"hey there what's your name"<<endl;
goto here;
}
else if(! strcasecmp ("How are you?" str)) {
cout<<"I'm fine sir"<<endl; 
goto here;   
}
//the program will keep running as long as input is given 
return 0;   
}
