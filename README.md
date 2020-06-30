#include<iostream>
#include<string>
using namespace std;

struct Student
{
    string firstname;
    string lastname;
    int age;
};

int main()
{
    Student stud1, stud2, stud3;
    
    cout<<"The first name of The Student 1 is: ";
    cin>>stud1.firstname;
    
    cout<<"The last name of The Student 1 is: ";
    cin>>stud1.lastname;
    
    cout<<"The age of The Student 1 is: ";
    cin>>stud1.age;
    
    cout<<"The first name of The Student 2 is: ";
    cin>>stud2.firstname;
    
    cout<<"The last name of The Student 2 is: ";
    cin>>stud2.lastname;
    
    cout<<"The age of The Student 2 is: ";
    cin>>stud2.age;
    
    cout<<"The first name of The Student 3 is: ";
    cin>>stud3.firstname;
    
    cout<<"The last name of The Student 3 is: ";
    cin>>stud3.lastname;
    
    cout<<"The age of The Student 3 is: ";
    cin>>stud3.age;
    
    cout<<"The characteristics of The Student 1:"<<endl<<"Firstname: "<<stud1.firstname<<endl<<"Lastname: "<<stud1.lastname<<endl<<"Age: "<<stud1.age<<endl;
    cout<<"The characteristics of The Student 2:"<<endl<<"Firstname: "<<stud2.firstname<<endl<<"Lastname: "<<stud2.lastname<<endl<<"Age: "<<stud2.age<<endl;
    cout<<"The characteristics of The Student 3:"<<endl<<"Firstname: "<<stud3.firstname<<endl<<"Lastname: "<<stud3.lastname<<endl<<"Age: "<<stud3.age<<endl;
    
    return 0;
}

