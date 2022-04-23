# default-constructor-parametrize-constructor-
using System;
using System.Linq;
using System.Collections.Generic;
namespace HelloWorld
{
    Public class Program 
    {

  Int r;
  String n;
  Program(int rollno,string name)
     {
             r=rollno;
             n=name;
           Console.WriteLine(r+”\t“+n);
      }
      Program()
      {
       Console.WriteLine(“Constructor called”);
      }
     Public static void Main(string [] args)
  {
	Program p=new Program();
         Program p1=new Program(114,”Nandini”);
     	}
      }
 }
