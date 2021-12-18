# Biography-2
#display name, age and hometown
#include<iostream>
using namespace std;
int main()
{
    string name;      //declaring variable 'name' with datatype string
    string hometown;    //declaring variable 'hometown' with datatype string
    int age;       //declaring variable 'age' with datatype integer
    cout << "\nEnter your name : ";  
    cin >> name;
    cout << "\nEnter your hometown : ";  //asking the user to enter hometown
    cin >> hometown;   //storing the user input using cin function
    cout << "\nEnter your age : ";
    cin >> age;
    cout << "\nNAME : " << name << endl;  
    cout << "\nHOMETOWN : " << hometown << endl;/*displaying name, age and 
                                          hometown to the console screen*/
    cout << "\nAGE : " << age << endl;
    return 0;
}
