#include<iostream>
#include<iomanip>
using namespace std;
class student
{
int roll;
string dep,name,year;
public:
void read();
void show();
void update();
void del();
};
void student::read()
{
cout<<"Enter the Student Name: ";
cin>>name;
cout<<"Enter the Roll No. of Student: ";
cin>>roll;
cout<<"Enter the Department of student: ";
cin>>dep;
cout<<"Enter the Year of studing: ";
cin>>year;
}
void student::show()
{
cout<<"Student Details are:"<<endl
<<"Name: "<<name<<endl
<<"Roll No.: "<<roll<<endl
<<"Departement: "<<dep<<endl
<<"Current Year: "<<year<<endl;
}
void student::update()
{ 
int q;
string choice;
cout << "The choice are: " << endl
<< "1:Edit name." << endl
<< "2:Edit Roll No." << endl
<< "3:Edit Department." << endl
<< "4:Edit Year"<<endl;
do
{ cout<<endl;
cout<<"Selcte the choice:"<<endl;
cin>>q;
switch (q)
{
case 1: cout<<"Enter the Student Name: ";
cin>>name;
break;
case 2: cout<<"Enter the Roll No. of Student: ";
cin>>roll;
break;
case 3: cout<<"Enter the Department of student: ";
cin>>dep;
break;
case 4: cout<<"Enter the Year of studing: ";
cin>>year;
break;
default:
cout << "The choice selected by you is invalid.";
}
cout<<"Do you Wan't continue(Yes/No) : "<<endl;
cin>>choice;
}while(choice == "Yes"); 
}
void student:: del(){
roll = 0; 
dep= "NA"; 
year = "NA"; 
name = "NA";
}
int main()
{
student s1;
student *p;
p = &s1;
int count =1;
int ch;
cout << "The choices number are as following: " << endl
<< "1:Fill the profile." << endl
<< "2:Update the information." << endl
<< "3:Delet the Information." << endl
<< "4:Display Information."<<endl
<< "5:Exit."<<endl<<endl;
while (count == 1)
{ cout<<endl;
cout <<"Enter the choice: ";
cin >> ch;
switch (ch)
{
case 1:
p->read();
break;
case 2:
p->update();
break;
case 3:
p->del();
break;
case 4:
p->show();
break;
case 5:count = 0;
break;
default:
cout << "The choice selected by you is invalid.";
}
} 
return 0;
}
