#include<iostream.h>
#include<conio.h>
class hosp
{
int k;
char my_word[31];
public:
void time()
{
cout<<"\nWorking Days Of Hospital: Monday to Saturday\nHospital Timing: 12am 
to 12pm";
}
void eapp(char ch)
{
cout<<"\nEnter Name Of Person To Check For Existing Appointment: ";
cin>>ch;
cout<<"Sorry sir,looks like the name you written does not match from our data";
}
void app()
{
cout<<endl<<"Enter Name Of Person To Get An Appointment:";
cin>>my_word;
cout<<"\nEnter Age:";
cin>>k;
cout<<endl<<"Enter Disease:";
cin>>my_word;
cout<<"\n****Appointment Added Succesfully****";
}
void dav()
{
cout<<endl<<"Doctor's Name\tQualification\t\tStatus";
cout<<"\nDr.Dalal \tMD\t\tAvailable from Thu to Sat";
cout<<"\nDr.Shakeel \tBUMS\t\tAvailable from Mon to Sat";
cout<<"\nDr.Sanjay \tMBBS\t\tAvailable from Mon to wed";
cout<<"\nDr.Ankita \tMBBS\t\tNot Available";
cout<<"\nDr.Rajendra \tMD\t\tAvailable on Fri-Sat";
cout<<"\nDr.Vijay \tBUMS\t\tNot Available";
}
void pat()
{
cout<<"\nPatient's Name\t\tAge\tGender\t\tDisease";
cout<<"\nRaj kumar\t\t32\tMale\t\tBrain Cancer";
cout<<"\nObaid\t\t\t17\tMale\t\tFever,Cold";
cout<<"\nVinod\t\t\t69\tMale\t\tTuberCulosis";
cout<<"\nSunderlal\t\t55\tMale\t\tTyphoid";
cout<<"\nRakesh\t\t\t47\tMale\t\tPneumonia";
cout<<"\nSavita\t\t\t89\tFemale\t\tBlood Cancer";
}
};
void main()
{ hosp s1;
int i,j;
char c,c1;
clrscr();
cout<<"\t\t\t\t******HELLO******\n\t\t\t******WELCOME TO CITY 
HOSPITAL******";
cout<<"\n\t\t\tPlease Enter Coressponding Number";
cout<<"\n1.Check Hospital Time\n2.Check For Existing Appointment\n3.Get An 
Appointment\n4.Check Doctor's Availability\n5.Get Existing Patient's Details";
cout<<"\nEnter The Number: ";
cin>>i;
switch(i)
{
case 1:
s1.time();
break;
case 2:
s1.eapp(c);
break;
case 3:
s1.app();
break;
case 4:
s1.dav();
break;
case 5:
s1.pat();
break;
default:
cout<<"Please Enter Valid Number";
break;
}
getch();
}
