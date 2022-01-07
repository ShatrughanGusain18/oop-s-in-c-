#include <iostream>
#include <string>

char grade(int marks[]);
void details(std::string name,int roll_num,int marks[] );

char grade(int marks[])
{
  int sum=0; double avrg=0;
  for(int i=0;i<5;i++)
  {
    sum=marks[i]+sum;
  }
  avrg=sum/5;
  if(avrg>=90)
  {
    return 'A';
  }
  else if(avrg>=80)
  {
    return 'B';
  }
  else if(avrg>=70)
  {
    return 'C';
  }
  else if(avrg>=60)
  {
    return 'D';
  }
  else if(avrg>=50)
  {
    return 'E';
  }
  else{
    return 'F';
  }
}

void details(std::string name,int roll_num,int marks[] )
{
  std::cout<<std::endl<<std::endl<<"Student Details : "<<std::endl;
  std::cout<<"Name : "<<name<<std::endl;
  std::cout<<"Roll Number : "<<roll_num<<std::endl;
  std::cout<<"Operating System : "<<marks[0]<<std::endl;
  std::cout<<"Data Structure : "<<marks[1]<<std::endl;
  std::cout<<"Obect Oriented Programming with C++ : "<<marks[2]<<std::endl;
  std::cout<<"Web Technologies : "<<marks[3]<<std::endl;
  std::cout<<"Genric : "<<marks[4]<<std::endl;
  std::cout<<"Grade : "<<grade(marks);
}

int main()
{
  int roll_num,marks[5];
  std::string name;
  std :: cout << "Enter Student name ";
  getline(std::cin,name);
  std :: cout << "Enter your Roll Number ";
  std :: cin >> roll_num;
  std :: cout<<"enter marks of Operating System ";
  std :: cin>>marks[0];
  std :: cout<<"enter marks of Data Strucutures ";
  std :: cin>>marks[1];
  std :: cout<<"enter marks of Obect Oriented Programming with C++ ";
  std :: cin>>marks[2];
  std :: cout<<"enter marks of Web Technologies ";
  std :: cin>>marks[3];
  std :: cout<<"enter marks of Genric Subject ";
  std :: cin>>marks[4];
  details(name,roll_num,marks);
}
