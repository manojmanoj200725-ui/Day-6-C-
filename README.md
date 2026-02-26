# Day-6-C-
C++ Calculator
\// Online C++ compiler to run C++ program online
#include <iostream.h>
#include<conio.h>
#include<math.h>
    void main()
    {
     int a,b,ch;
     clrscr();
     cout<<"enter a two number:"<<endl;
     cin>>a>>b;
     cout<<"1.addtion="<<endl;
     cout<<"2.subtraction="<<endl;
     cout<<"3.multiplication="<<endl;
     cout<<"4.Division="<<endl;
     cin>>ch;
     switch(ch)
     {
     case 1:
     cout<<"Add="<<a+b<<endl;
     break;
     case 2:
     cout<<"sub="<<a-b<<endl;
     break;
     case 3:
     cout<<"multiplie="<<a*b<<endl;
     break;
     case 4:
     cout<<"Div="<<a/b<<endl;
     break;
     default:cout<<"invalid choice"<<endl;
     getch();
    }
    }
