//**********************************************************
// INCLUDED HEADER FILES
//**********************************************************

#include<stdlib.h>
#include<fstream.h>
#include<conio.h>
#include<process.h>
#include<dos.h>
#include<stdio.h>
#include<ctype.h>
#include<string.h>
//**********************************************************
// GLOBAL: CLASS
//**********************************************************
void admin();

class studentclass
  {
 public:
 char name[30],homeaddress[100],email[30],parentname1[34],parentname2[34];
 char gender[10],bg[10],mobileno2[10],mobileno1[10],aadharno[12],income[6];
 int rollno,verify;
   void students();
   void showstudent();
   int getrollno();
   void showspec_stu(int);
   void newstudent();
   void destroystudent();
   void modifystudent();
   void searchstudent();
   /*\
   void workers();
   void officemembers();
   */
   }user1;


class facultyclass
  {
 public:
 char name[30],homeaddress[100],email[30],parentname1[34],parentname2[34];
 char qualifi[30],gender[10],bg[10],mobileno2[10],mobileno1[10],aadharno[12],income[6];
 char semail[30],sdesig[50],sname[30],sbg[10],sgender[10],squalifi[50];
 char smobileno1[10],saadharno[10],smobileno2[10],ans;
 int code;
   void faculty();
   int  getcode()
   {
     return code;
   }
   void showfaculty();
   void showspec_fac(int);
   void newfaculty();
   void destroyfaculty();
   void modifyfaculty();
   void searchfaculty();
   void newstudent();
   void searchstudent();
 /*
   void workers();
   void officemembers();
 */
   }user,use[20];

//**********************************************************
// GLOBLE FUNCTION FOR EDITTING BY THE ADMIN
//**********************************************************
class line
{public:
 void printtask();
 void edit_task();
 void attendance();
 void add_task();
 void setting();
 void birthday();
 void clearup(void);
 void print();
 void printsms();
 }lin;
 void line::clearup()
{
	for (int i=25; i>=1; i--)
	{
		delay(20) ;
		gotoxy(1,i) ; clreol() ;
	}
}
/* void printsms()
 {textcolor (11);
for(int i=0;i<10;i++)
{

delay(100);
textcolor(i+2345234);
clrscr();
gotoxy(i+9,10); cout<<"±ÛÛÛÛÛÛ±\n\r";
gotoxy(i+9,11); cout<<"±Û\n\r";
gotoxy(i+9,12); cout<<"±±\n\r";
gotoxy(i+9,13); cout<<"ÛÛÛÛÛÛÛ±\n\r";
gotoxy(i+9,14); cout<<"      Û±\n\r";
gotoxy(i+9,15); cout<<"      ±±\n\r";
gotoxy(i+9,16); cout<<"±ÛÛÛÛÛÛÛCHOOL\n\r";

gotoxy(41-i,1+i);cout<<"ÛÛ±   ±ÛÛ\n\r";
gotoxy(41-i,2+i);cout<<"±±Û± ±Û±± \n\r";
gotoxy(41-i,3+i);cout<<"±Û Û±Û Û±\n\r";
gotoxy(41-i,4+i);cout<<"±Û  Û  Û±\n\r";
gotoxy(41-i,5+i);cout<<"±Û     Û±\n\r";
gotoxy(41-i,6+i);cout<<"±Û     Û±\n\r";
gotoxy(41-i,7+i);cout<<"±±     ±±ANAGEMENT\n\r";

gotoxy(60-i,10); cout<<"±ÛÛÛÛÛÛ±\n\r";
gotoxy(60-i,11); cout<<"±Û\n\r";
gotoxy(60-i,12); cout<<"±±\n\r";
gotoxy(60-i,13); cout<<"ÛÛÛÛÛÛÛ±\n\r";
gotoxy(60-i,14); cout<<"      Û±\n\r";
gotoxy(60-i,15); cout<<"      ±±\n\r";
gotoxy(60-i,16); cout<<"±ÛÛÛÛÛÛÛYSTEM\n\r";
delay(250);
    }
gotoxy(33,20); cout<<"A C++ PROJECT BY:\n\r";
gotoxy(33,21); cout<<"               S.SUGHEESHAN GRADE:XII\n\r";
gotoxy(33,22); cout<<"               R.ADITHYA    GRADE:XII\n\r";
delay(100);



getch();

 }*/
 void line:: print()
{
 clrscr();
 int i=10,j=8;
gotoxy(i,j++);cout<<"ÛßßßßßßßßßÛ";
gotoxy(i,j++);cout<<"Û  ÜÜÜÜÜ  Û";
gotoxy(i,j++);cout<<"Û Û     Û Û";
gotoxy(i,j++);cout<<"Û Û     Û Û";
gotoxy(i,j++);cout<<"Û ÛÜÜÜÜÜÛ Û";
gotoxy(i,j++);cout<<"Û Û     Û Û";
gotoxy(i,j++);cout<<"Û Û     Û Û";
gotoxy(i,j++);cout<<"ÛÜÜÜÜÜÜÜÜÜÛ";
gotoxy(i,++j);cout<<"    |->| ";
delay(100);
i=35,j=8;
gotoxy(i,j++);cout<<"ÛßßßßßßßßßÛ";
gotoxy(i,j++);cout<<"Û ÜÜÜÜÜÜÜ Û";
gotoxy(i,j++);cout<<"Û    Û    Û";
gotoxy(i,j++);cout<<"Û    Û    Û";
gotoxy(i,j++);cout<<"Û    Û    Û";
gotoxy(i,j++);cout<<"Û    Û    Û";
gotoxy(i,j++);cout<<"Û    Û    Û";
gotoxy(i,j++);cout<<"ÛÜÜÜÜÜÜÜÜÜÛ";
gotoxy(i,++j);cout<<"    |->| ";
delay(100);
i=60,j=8;
gotoxy(i,j++);cout<<"ÛßßßßßßßßÛ";
gotoxy(i,j++);cout<<"Û ÜÜÜÜÜÜ Û";
gotoxy(i,j++);cout<<"Û Û      Û";
gotoxy(i,j++);cout<<"Û Û      Û";
gotoxy(i,j++);cout<<"Û ßßßßßÛ Û";
gotoxy(i,j++);cout<<"Û      Û Û";
gotoxy(i,j++);cout<<"Û ÜÜÜÜÜÛ Û";
gotoxy(i,j++);cout<<"ÛÜÜÜÜÜÜÜÜÛ";
gotoxy(i,++j);cout<<"    |->| ";
//getch();
delay(500);
char ch,flag=13,c;
gotoxy(40,15);
  while(ch!=13)
   {
   once:
   c=ch;
   ch=getch();
   if(ch=='a')
    {
    gotoxy(16,17);
    }
   if(ch=='s')
    {
    gotoxy(66,17);
    }
   if(ch=='t')
    {
    gotoxy(41,17);
    }
   }
lin.clearup();
switch (c)
{
case 'a':admin();break;
case 't':user.faculty();break;
case 's':user1.students();break;
}
}
void line::  birthday()
{int i=11,j=57;
gotoxy(j,i++);cout<<"É------------------» ";
gotoxy(j,i++);cout<<"|WHISHING MANY MORE|";
gotoxy(j,i++);cout<<"|RETURNS OF THE DAY|";
gotoxy(j,i++);cout<<"| É  »   TO  É  »  |";
gotoxy(j,i++);cout<<"|                  |";
gotoxy(j,i++);cout<<"| È  ¼       È  ¼  |";
gotoxy(j,i++);cout<<"|TEACHERS  STUDENTS|";
gotoxy(j,i++);cout<<"È------------------¼ ";
for(int m=0;m<=3;m++)
{
gotoxy(60,15);cout<<"0";
gotoxy(61,15);cout<<m;
delay(50);
}
for(int k=0;k<=7;k++)
{
gotoxy(71,15);cout<<"0";
gotoxy(72,15);cout<<k;
delay(50);
}

}
//**********************************************************
// ATTENDANCE
//**********************************************************
void line:: attendance()
{
int i=9,j=2,b=12,v=20;
gotoxy(j,i++);cout<<"É---------------------»";
gotoxy(j,i++);cout<<"|  PRESENT THIS YEAR  |";
gotoxy(j,i++);cout<<"|   É»           É»   |";
gotoxy(j,i++);cout<<"| É    »       É    » |";
gotoxy(j,i++);cout<<"|                     |";
gotoxy(j,i++);cout<<"|  È  ¼         È  ¼  |";
gotoxy(j,i++);cout<<"|FACULTIES    STUDENTS|";
gotoxy(j,i++);cout<<"|      HOSTELLERS     |";
gotoxy(j,i++);cout<<"|          É»         |";
gotoxy(j,i++);cout<<"|        É    »       |";
gotoxy(j,i++);cout<<"|                     |";
gotoxy(j,i++);cout<<"|         È  ¼        |";
gotoxy(j,i++);cout<<"È---------------------¼";
for(int a=0,s=0;a<=75,s<=1350;a++,s++)
{
if(a>75)
a--;
gotoxy(6,13);cout<<a;
delay(1);
gotoxy(18,13);cout<<s;
delay(1);
}
for(int h=0;h<=1000;h++)
{
gotoxy(12,19);cout<<h;
delay(1);
}
}
//**********************************************************
// PRINTING TASK
//**********************************************************
void line:: printtask()
{ int i=11,j=30;
gotoxy(j,i++);cout<<"É------------------» ";
gotoxy(j,i++);cout<<"|  TASK TO BE DONE |";
gotoxy(j,i++);cout<<"È------------------¼ ";
gotoxy(j,i++);cout<<" É----------------» ";
gotoxy(j,i++);cout<<" |       Û        |";
gotoxy(j,i++);cout<<" |     þþþþ      |";
gotoxy(j,i++);cout<<" |       Û        |";
gotoxy(j,i++);cout<<" È----------------¼ ";
}
//**********************************************************
// ADDING TASK
//**********************************************************
void line:: add_task()
{
clrscr();
for(int j=0;j<20;j++)
       {
       clrscr();
       gotoxy(j+3,5);cout<<"<<<THE TASK TO BE DONE>>>";

       gotoxy(j,9);cout<< "<<<24th SEPTEMBER,2019>>>"<<endl;
       gotoxy(j,10);cout<<"ÉÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ» "<<endl;
       gotoxy(j,11);cout<<"º*PRACTICE SESSION FOR KIDDIES. º "<<endl;
       gotoxy(j,12);cout<<"º*SPORTS DAY PRACTICE.          º "<<endl;
       gotoxy(j,13);cout<<"º*TUTORS AND FACULTIES MEETING  º "<<endl;
       gotoxy(j,14);cout<<"º WITH Sr.PRINCIPAL.            º "<<endl;
       gotoxy(j,15);cout<<"º*RALLY ON SAVING AGRICULTURE.  º "<<endl;
       gotoxy(j,16);cout<<"º*DISCUSSION ABOUT MT_5.        º "<<endl;
       gotoxy(j,17);cout<<"º                               º "<<endl;
       gotoxy(j,18);cout<<"ÈÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ¼ "<<endl;
       delay(50);
       }
  }
//**********************************************************
// SETTINGS FUNCTION
//**********************************************************
void setting()
 {
clrscr();
char pick;
clrscr();
for(int j=0;j<20;j++)
       {
       clrscr();
       gotoxy(j+3,5);cout<<"<<<CHOOSE WHAT TO BE EDITED>>>";
       gotoxy(j,10);cout<<"ÉÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ» "<<endl;
       gotoxy(j,11);cout<<"º      1.FACULTY                º "<<endl;
       gotoxy(j,12);cout<<"º      2.STUDENTS               º "<<endl;
       gotoxy(j,13);cout<<"º      3.WORKERS                º "<<endl;
       gotoxy(j,14);cout<<"º      4.OFFICE MEMBERS         º "<<endl;
       gotoxy(j,15);cout<<"º      5.ADMIN EDIT             º "<<endl;
       gotoxy(j,16);cout<<"º      6.EXIT                   º "<<endl;
       gotoxy(j,17);cout<<"º  ??ENTER CHOICE>>.....?       º "<<endl;
       gotoxy(j,18);cout<<"ÈÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ¼ "<<endl;
       delay(50);
       }
       gotoxy(45,17);pick=getch();
       delay(100);
 switch(pick)
   {
  case 49:
     user.faculty();
     break;
  case 50:
     user1.students();
     break;
  case 51:
     //user.workers();
     break;
  case 52:
      // user.officemembers();
     break;
  case 53:
    // user.adminedit();
     break;
  case 54:
    gotoxy(35,14);cout<<"\n THANK YOU!! SEE YOU SOON";
    exit(-1);
    break;
  default:
     cout<<"\n choose from (1~5) only!!!";
      break;
	}
  getch();
  }

//**********************************************************
// GLOBAL ADMIN FUNCTION
//**********************************************************
void admin()
{  char move;int h=0,s=0;
  clrscr();
  gotoxy(33,1);cout<<"É-------------»                  ";
  gotoxy(33,2);cout<<"|WELCOME ADMIN|                     ";
  gotoxy(33,3);cout<<"È-------------¼                     È»Setting  ";
  gotoxy(29,5);cout<< "<<<24th SEPTEMBER,2019>>>"<<endl;
  gotoxy(5,3);cout<<" Details  ";

     lin.printtask();
     lin.birthday();
     lin.attendance();
  gotoxy(1,1);
   for(;;)
     {
      move=getch();
    if(move=='d')
      gotoxy(s++,h);
    else if(move=='a')
      s--;
    else if(move=='w')
      h--;
    else if(move=='s')
      h++;
    else if(move=='x')
      exit(1);
      gotoxy(s,h);
  if((s==71)&&(h==2))
      {
      setting();
	break;
      }
  if((s==38)&&(h==16))
      {
     lin.edit_task();
	break;
      }

     }

getch();
}
//**********************************************************
// FUNCTION TO EDIT FACULTY
//**********************************************************

void facultyclass::faculty()
    {
    clrscr();
  char pickit;
   for(int j=0;j<20;j++)
       {
       clrscr();
       gotoxy(j+3,5);cout<<"<<<CHOOSE WHAT TO BE EDITED>>>";
       gotoxy(j,10);cout<<"ÉÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ» "<<endl;
       gotoxy(j,11);cout<<"º      1.ADD FACULTY            º "<<endl;
       gotoxy(j,12);cout<<"º      2.MODIFY FACULTY         º "<<endl;
       gotoxy(j,13);cout<<"º      3.SHOW FACULTY           º "<<endl;
       gotoxy(j,14);cout<<"º      4.DELETE FACULTY         º "<<endl;
       gotoxy(j,15);cout<<"º      5.BACK TO MAIN           º "<<endl;
       gotoxy(j,16);cout<<"º      6.EXIT                   º "<<endl;
       gotoxy(j,17);cout<<"º  ??ENTER CHOICE>>.....?       º "<<endl;
       gotoxy(j,18);cout<<"ÈÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ¼ "<<endl;
       delay(50);
       }
	gotoxy(45,17);pickit=getch();
       delay(100);
 switch(pickit)
   {
  case 49:
     user.newfaculty();
     break;
  case 50:
     //user.modifyfaculty();
     break;
  case 51:
     user.searchfaculty();
     break;
  case 52:
    // user.destroyfaculty();
     break;
  case 53:
     lin.print();
     break;
  case 54:
    gotoxy(35,14);cout<<"\n THANK YOU!! SEE YOU SOON";
    exit(-1);
    break;
  default:
      cout<<"\n choose from (1~5) only!!!";
      break;
     }
  }
//**********************************************************
// FUNCTION TO EDIT STUDENT
//**********************************************************

void studentclass::students()
    {
    clrscr();
  char pickit;
   for(int j=0;j<20;j++)
       {
       clrscr();
       gotoxy(j+3,5);cout<<"<<<CHOOSE WHAT TO BE EDITED>>>";
       gotoxy(j,10);cout<<"ÉÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ» "<<endl;
       gotoxy(j,11);cout<<"º      1.ADD STUDENT            º "<<endl;
       gotoxy(j,12);cout<<"º      2.MODIFY STUDENT         º "<<endl;
       gotoxy(j,13);cout<<"º      3.SHOW STUDENT           º "<<endl;
       gotoxy(j,14);cout<<"º      4.DELETE STUDENT         º "<<endl;
       gotoxy(j,15);cout<<"º      5.BACK TO MAIN           º "<<endl;
       gotoxy(j,16);cout<<"º      6.EXIT                   º "<<endl;
       gotoxy(j,17);cout<<"º  ??ENTER CHOICE>>.....?       º "<<endl;
       gotoxy(j,18);cout<<"ÈÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ¼ "<<endl;
       delay(50);
       }
	gotoxy(45,17);pickit=getch();
       delay(100);
 switch(pickit)
   {
  case 49:
     user1.newstudent();
     break;
  case 50:
     //user1.modifystudent();
     break;
  case 51:
     user1.searchstudent();
     break;
  case 52:
    // user1.destroystudent();
     break;
  case 53:
     lin.print();
     break;
  case 54:
    gotoxy(35,14);cout<<"\n THANK YOU!! SEE YOU SOON";
    exit(-1);
    break;
  default:
      cout<<"\n choose from (1~5) only!!!";
      break;
     }
  }

//**********************************************************
// FUNCTION FOR ADDING FACULTY
//**********************************************************
void facultyclass::newfaculty()
   {
   char flag1,flag2;
   ofstream file ;
   file.open("faculty.dat", ios::app) ;
   clrscr();
   flag2='N';
   while(flag2!='Y')
    {
     flag1='N';
     while(flag1!='Y')
     {
      clrscr();
    //code=addcode();
      gotoxy(15,2);cout<<"PLEASE FILL IN THE DETAILS ...";
      gotoxy(25,5);cout<<"YOUR MEMORANDA";
      cout<<"\nENTER CODE:";cin>>code;file<<code<<"\n";
      gotoxy(5,8);cout<<"Name: ";
      gotoxy(5,10);cout<<"Gender: ";
      gotoxy(30,10);cout<<"Blood Group: ";
      gotoxy(5,12);cout<<"Address: ";
      gotoxy(5,14);cout<<"Mail ID: ";
      gotoxy(5,16);cout<<"Fathers Name: ";
      gotoxy(30,16);cout<<"Mothers Name: ";
      gotoxy(5,18);cout<<"Mobile NO1: ";
      gotoxy(30,18);cout<<"Mobile No2: ";
      gotoxy(5,20);cout<<"Aadhar No: ";
      gotoxy(10,22);cout<<"Is the information correct(y/n)?? ";
      gotoxy(10,8);gets(name);file<<name<<"\n";
      gotoxy(13,10);gets(gender);file<<gender<<"\n";
      gotoxy(43,10);gets(bg);file<<bg<<"\n";
      gotoxy(14,12);gets(homeaddress);file<<homeaddress<<"\n";
      gotoxy(13,14);gets(email);file<<email<<"\n";
      gotoxy(19,16);gets(parentname1);file<<parentname1<<"\n";
      gotoxy(44,16);gets(parentname2);file<<parentname2<<"\n";
      gotoxy(17,18);cin>>mobileno1;file<<mobileno1<<"\n";
      gotoxy(42,18);cin>>mobileno2;file<<mobileno2<<"\n";
      gotoxy(16,20);cin>>aadharno;file<<aadharno<<"\n";
      gotoxy(45,22);cin>>flag1;
    flag1=toupper(flag1);
   }
  flag1='N';
  while(flag1!='Y')
  {

   clrscr();

   gotoxy(15,2);cout<<"PLEASE FILL IN THE DETAILS ...";
   gotoxy(25,5);cout<<"YOUR MARITIAL & FINANCE MEMORANDA ";
   gotoxy(5,8);cout<<"Spouse Name: ";
   gotoxy(5,10);cout<<"Gender: ";
   gotoxy(30,10);cout<<"Blood Group: ";
   gotoxy(5,12);cout<<"Designation: ";
   gotoxy(5,14);cout<<"Qualification: ";
   gotoxy(5,16);cout<<"Mail ID: ";
   gotoxy(35,16);cout<<"Family Income: ";
   gotoxy(5,18);cout<<"Mobile NO1: ";
   gotoxy(30,18);cout<<"Mobile No2: ";
   gotoxy(5,20);cout<<"Aadhar No: ";
   gotoxy(10,22);cout<<"Is the information correct(y/n)?? ";
   gotoxy(18,8);gets(sname);file<<sname<<"\n";
   gotoxy(13,10);gets(sgender);file<<sgender<<"\n";
   gotoxy(43,10);gets(sbg);file<<sbg<<"\n";
   gotoxy(18,12);gets(sdesig);file<<sdesig<<"\n";
   gotoxy(20,14);gets(squalifi);file<<squalifi<<"\n";
   gotoxy(13,16);gets(semail);file<<semail<<"\n";
   gotoxy(50,16);cin>>income;file<<income<<"\n";
   gotoxy(17,18);cin>>smobileno1;file<<smobileno1<<"\n";
   gotoxy(42,18);cin>>smobileno2;file<<smobileno2<<"\n";
   gotoxy(16,20);cin>>saadharno;file<<saadharno<<"\n";
   gotoxy(45,22);cin>>flag1;
   flag1=toupper(flag1);
  }
  clrscr();
   {
   file.close();
gotoxy(35,14);cout<<"SAVING";
 for(int i=0;i<=5;i++)
 {
   delay(500);
   cout<<".";
 }
  clrscr();
for(int j=0;j<15;j++)
{
clrscr();
gotoxy(j,6); cputs("        ÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ");
gotoxy(j,7); cputs("            ÜÜÜÜÜÜ  ÜÜÜÜÜÜ       ");
gotoxy(j,8); cputs("             Û   Û  Û    Û ");
gotoxy(j,9); cputs("             Û   Û  Û    Û ");
gotoxy(j,10);cputs("             Û   Û  Û    Û ");
gotoxy(j,11);cputs("            ÜÛÜÜÜÛ  ÛÜÜÜÜÛ ");
gotoxy(j,12); cputs("       ÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ");

gotoxy(55-j,6); cputs("ÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ \n\r");
gotoxy(55-j,7); cputs(" Ü    Ü ÜÜÜÜÜÜ   \n\r");
gotoxy(55-j,8); cputs(" ÛÛ   Û Û         \n\r");
gotoxy(55-j,9); cputs(" Û Û  Û ÛÜÜÜ     \n\r");
gotoxy(55-j,10);cputs(" Û  Û Û Û         \n\r");
gotoxy(55-j,11);cputs(" Û   ÛÛ ÛÛÛÛÛÛ  \n\r");
gotoxy(55-j,12);cputs("ÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ \n\r");

delay(80);
}

   gotoxy(10,22);cout<<"Is the information correct(y/n)?? ";
    gotoxy(45,22);cin>>flag2;
   flag2=toupper(flag2);
  }
 //delay(1000);
 clrscr();
 cout<<"\t YOUR CODE IS:"<<code;
 delay(100);
 cout<<"\n \t DO YOU WANT TO VIEW IT?(Y/N):";
   cin>>ans;
   if(ans=='y'||ans=='Y')
     showfaculty();
}
}
//**********************************************************
// FUNCTION TO ADD STUDENT
//**********************************************************

void studentclass::newstudent()
   {char flag1,flag2,ans;
    ofstream file ;
    file.open("pupil.dat", ios::app) ;
  clrscr();
  flag2='N';


  while(flag2!='Y')
  {

  flag1='N';
  while(flag1!='Y')
  {
   clrscr();
   //code=addcode();
   gotoxy(15,2);cout<<"PLEASE FILL IN THE DETAILS ...";
   gotoxy(25,5);cout<<"YOUR MEMORANDA";
   cout<<"\nENTER ROLL:";cin>>rollno;file<<rollno<<"\n";
   gotoxy(5,8);cout<<"Name: ";
   gotoxy(5,10);cout<<"Gender: ";
   gotoxy(30,10);cout<<"Blood Group: ";
   gotoxy(5,12);cout<<"Address: ";
   gotoxy(5,14);cout<<"Mail ID: ";
   gotoxy(5,16);cout<<"Fathers Name: ";
   gotoxy(30,16);cout<<"Mothers Name: ";
   gotoxy(5,18);cout<<"Mobile NO1: ";
   gotoxy(30,18);cout<<"Mobile No2: ";
   gotoxy(5,20);cout<<"Aadhar No: ";
   gotoxy(35,20);cout<<"Family Income: ";
   gotoxy(10,22);cout<<"Is the information correct(y/n)?? ";
   gotoxy(10,8);gets(name);file<<name<<"\n";
   gotoxy(13,10);gets(gender);file<<gender<<"\n";
   gotoxy(43,10);gets(bg);file<<bg<<"\n";
   gotoxy(14,12);gets(homeaddress);file<<homeaddress<<"\n";
   gotoxy(13,14);gets(email);file<<email<<"\n";
   gotoxy(19,16);gets(parentname1);file<<parentname1<<"\n";
   gotoxy(44,16);gets(parentname2);file<<parentname2<<"\n";
   gotoxy(17,18);cin>>mobileno1;file<<mobileno1<<"\n";
   gotoxy(42,18);cin>>mobileno2;file<<mobileno2<<"\n";
   gotoxy(16,20);cin>>aadharno;file<<aadharno<<"\n";
   gotoxy(49,20);cin>>income;
   gotoxy(45,22);cin>>flag1;
   flag1=toupper(flag1);
  }
  flag1='N';
  clrscr();
 file.close() ;
gotoxy(35,14);cout<<"SAVING";
 for(int i=0;i<=5;i++)
 {
   delay(500);
   cout<<".";
 }
  clrscr();
for(int j=0;j<15;j++)
{
clrscr();
gotoxy(j,6); cputs("        ÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ");
gotoxy(j,7); cputs("            ÜÜÜÜÜÜ  ÜÜÜÜÜÜ       ");
gotoxy(j,8); cputs("             Û   Û  Û    Û ");
gotoxy(j,9); cputs("             Û   Û  Û    Û ");
gotoxy(j,10);cputs("             Û   Û  Û    Û ");
gotoxy(j,11);cputs("            ÜÛÜÜÜÛ  ÛÜÜÜÜÛ ");
gotoxy(j,12); cputs("       ÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ");

gotoxy(55-j,6); cputs("ÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ \n\r");
gotoxy(55-j,7); cputs(" Ü    Ü ÜÜÜÜÜÜ   \n\r");
gotoxy(55-j,8); cputs(" ÛÛ   Û Û         \n\r");
gotoxy(55-j,9); cputs(" Û Û  Û ÛÜÜÜ     \n\r");
gotoxy(55-j,10);cputs(" Û  Û Û Û         \n\r");
gotoxy(55-j,11);cputs(" Û   ÛÛ ÛÛÛÛÛÛ  \n\r");
gotoxy(55-j,12);cputs("ÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ \n\r");

delay(80);
}

   gotoxy(10,22);cout<<"Is the information correct(y/n)?? ";
    gotoxy(45,22);cin>>flag2;
   flag2=toupper(flag2);
  }
 //delay(1000);
 clrscr();
 cout<<"\t YOUR CODE IS:"<<rollno;
 delay(100);
 cout<<"\n \t DO YOU WANT TO VIEW IT?(Y/N):";
   cin>>ans;
   if(ans=='y'||ans=='Y')
     showstudent();
}
//**********************************************************
// FUNCTION TO SEARCH FOR THE FACULTY
//**********************************************************

void facultyclass::searchfaculty()
{
 clrscr();
  int a,b;int ecode;
  cout<<"\n ENTER THE CODE TO BE SEARCHED FOR:";
   cin>>ecode;
  user.showspec_fac(ecode);
}
//**********************************************************
// FUNCTION TO SEARCH FOR THE STUDENT
//**********************************************************

void studentclass::searchstudent()
{
 clrscr();
  int a,b;int rno;
  cout<<"\n ENTER THE CODE TO BE SEARCHED FOR:";
   cin>>rno;
  user1.showspec_stu(rno);
}
//**********************************************************
// FUNCTION TO SHOW THE FACULTY DETAILS
//**********************************************************

void facultyclass::showfaculty()
{ ifstream file ;
 file.open("faculty.dat", ios::in) ;
char flag;              //cout<<temp.getcode();
			gotoxy(15,2);cout<<"\n\n\t YOUR DETAILS ...";
			gotoxy(25,5);cout<<"YOUR PERSONAL MEMORANDA";
			gotoxy(5,8);cout<<"Name: "<<name;
			gotoxy(5,10);cout<<"Gender: "<<gender;
			gotoxy(30,10);cout<<"Blood Group: "<<bg;
			gotoxy(5,12);cout<<"Address: "<<homeaddress;
			gotoxy(5,14);cout<<"Mail ID: "<<email;
			gotoxy(5,16);cout<<"Fathers Name: "<<parentname1;
			gotoxy(30,16);cout<<"Mothers Name: "<<parentname2;
			gotoxy(5,18);cout<<"Mobile NO1: "<<mobileno1;
			gotoxy(30,18);cout<<"Mobile No2: "<<mobileno2;
			gotoxy(5,20);cout<<"Aadhar No: "<<aadharno;
			gotoxy(10,22);cout<<"goto next page(N)?? ";
			cin>>flag;
	    if(flag=='N'||flag=='n')
		   {
		    clrscr();

			gotoxy(25,5);cout<<"YOUR MARITIAL & FINANCE MEMORANDA ";
			gotoxy(5,8);cout<<"Spouse Name: ";puts(sname);
			gotoxy(5,10);cout<<"Gender: ";puts(sgender);
			gotoxy(30,10);cout<<"Blood Group: ";puts(sbg);
			gotoxy(5,12);cout<<"Designation: ";puts(sdesig);
			gotoxy(5,14);cout<<"Qualification: ";puts(squalifi);
			gotoxy(5,16);cout<<"Mail ID: ";puts(semail);
			gotoxy(35,16);cout<<"Family Income: "<<income;
			gotoxy(5,18);cout<<"Mobile NO1: "<<smobileno1;
			gotoxy(30,18);cout<<"Mobile No2: "<<smobileno2;
			gotoxy(5,20);cout<<"Aadhar No: "<<saadharno;
		    }
		    file.close();

}
//**********************************************************
// FUNCTION TO SHOW THE STUDENT DETAILS
//**********************************************************

void studentclass::showstudent()
{ ifstream file ;
 file.open("pupil.dat", ios::in) ;
			//cout<<temp.getcode();
			gotoxy(15,2);cout<<"\n\n\t YOUR DETAILS ...";
			gotoxy(25,5);cout<<"YOUR PERSONAL MEMORANDA";
			gotoxy(5,8);cout<<"Name: "<<name;
			gotoxy(5,10);cout<<"Gender: "<<gender;
			gotoxy(30,10);cout<<"Blood Group: "<<bg;
			gotoxy(5,12);cout<<"Address: "<<homeaddress;
			gotoxy(5,14);cout<<"Mail ID: "<<email;
			gotoxy(5,16);cout<<"Fathers Name: "<<parentname1;
			gotoxy(30,16);cout<<"Mothers Name: "<<parentname2;
			gotoxy(5,18);cout<<"Mobile NO1: "<<mobileno1;
			gotoxy(30,18);cout<<"Mobile No2: "<<mobileno2;
			gotoxy(5,20);cout<<"Aadhar No: "<<aadharno;
			gotoxy(10,22);cout<<"Family Income: "<<income;

   file.close();

}
//**********************************************************
// FUNCTION TO SPECIFIC FACULTY DETAILS
//**********************************************************

void facultyclass::showspec_fac(int ecode)
{
 char tr,found='n';

	ifstream file;
	file.open("faculty.txt", ios::in);
     while(!file.eof())
      {
      file>>code;
      file.getline(name,20);
      file.getline(gender,6);
      file.getline(bg,2);
      file.getline(homeaddress,50);
      file.getline(email,20);
      file.getline(parentname1,15);
      file.getline(parentname2,15);
      file>>mobileno1;
      file>>mobileno2;
      file>>aadharno;
      file.getline(sname,20);
      file.getline(sgender,6);
      file.getline(sbg,2);
      file.getline(sdesig,50);
      file.getline(squalifi,20);
      file.getline(semail,15);
      file>>income;
      file>>smobileno1;
      file>>smobileno2;
      file>>saadharno;
     if(user.getcode()==ecode)
	{
	   {found='y';
	    user.showfaculty();
	    break;
	  }
      }

      if(found=='n')
	  {
	   cout<<"FACULTY does not exist";
	   cout<<"\n WANT TO CREATE NEW?(Y/n):";cin>>tr;
	   if((tr=='Y')||(tr=='y')) user.newfaculty();
	   else lin.print();
	  }
    file.close();
     getch();
     }
     }

//**********************************************************
// FUNCTION TO SPECIFIC STUDENT DETAILS
//**********************************************************
void studentclass::showspec_stu(int rno)
{
 char tr,found='n';

	ifstream file;
	file.open("pupil.txt", ios::in);
     while(!file.eof())
      {
      file>>rollno;
      file.getline(name,20);
      file.getline(gender,6);
      file.getline(bg,2);
      file.getline(homeaddress,50);
      file.getline(email,20);
      file.getline(parentname1,15);
      file.getline(parentname2,15);
      file>>mobileno1;
      file>>mobileno2;
      file>>aadharno;
      file>>income;
      if(user1.rollno==rno)
       {
	   { user1.showstudent();
	    found='y';
	    break;
	  }
      }

      if(found=='n')
	  {
	   cout<<"STUDENT does not exist";
	   cout<<"\n WANT TO CREATE NEW?(Y/n):";cin>>tr;
	   if((tr=='Y')||(tr=='y')) user1.newstudent();
	   else lin.print();
	  }
    file.close();
     getch();
     }
     }
//**********************************************************
// FUNCTION TO PRNT TASK MENU
//**********************************************************

void line::edit_task()
{
int task_menu;
int pick;
repeat:
int z=10;
for(int j=0;j<20;j++)
       {
       clrscr();
       gotoxy(j+3,5);cout<<"<<<CHOOSE WHAT TO BE EDITED>>>";
       gotoxy(j,10);cout<<"ÉÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ» "<<endl;
       gotoxy(j,11);cout<<"º      1.ADD TASK               º "<<endl;
       gotoxy(j,12);cout<<"º      2.MODIFY TASK            º "<<endl;
       gotoxy(j,13);cout<<"º      3.VIEW TASK              º "<<endl;
       gotoxy(j,14);cout<<"º      4.EXIT                   º "<<endl;
       gotoxy(j,15);cout<<"º  <<ENTER CHOICE>>.....?       º "<<endl;
       gotoxy(j,16);cout<<"ÈÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ¼ "<<endl;
       delay(50);
       }
       gotoxy(45,17);pick=getch();
       delay(100);
  int today[10];
gotoxy(45,15);cin>>task_menu;
switch(task_menu)
   {
 case 1:
     lin.add_task();
     break;
 case 2:
     clrscr();
      cout<<"ENTER THE DATE THE TASK TO BE MODIFIED:24-09-2019";
     break;
 case 3:
       clrscr();

     cout<<"ENTER THE DATE THE TASK TO BE VIEW:24-09-2019";
     lin.add_task();
     gotoxy(15,15);
      cout<<"YOUR RESPONSBILITYS OF THE DAY ARE AS FOLLOWS";
     break;
 default:
     cout<<"\n wrong option sorry!!!!";
     delay(1000);
	 clrscr();
      goto repeat;
     break;
   }
}
void main()
{
textcolor(CYAN+GREEN+RED+BLUE);
textbackground(BLACK);
clrscr();
//lin.printsms();
lin.print();
getch();
}

