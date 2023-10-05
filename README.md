/******************************************************************************

Welcome to GDB Online.
GDB online is an online compiler and debugger tool for C, C++, Python, Java, PHP, Ruby, Perl,
C#, OCaml, VB, Swift, Pascal, Fortran, Haskell, Objective-C, Assembly, HTML, CSS, JS, SQLite, Prolog.
Code, Compile, Run and Debug online from anywhere in world.

*******************************************************************************/
using System;

public class Student
{
    public string Name;
    public int Age;
    public string SchoolID;
    public string Subject;
    public string Subject_code;
    public string School;
    public string Course;

    public Student(string name, string schoolID, string subject, string subject_code, string school, string course, int age)
    {
        Name = name;
        SchoolID = schoolID;
        Subject = subject;
        Subject_code = subject_code;
        School = school;
        Course = course;
        Age = age;
        

    } public void info(){
        Console.WriteLine(Name + SchoolID + Subject + Subject_code + School + Course + Age);
    } 
}

class HelloWorld
{
    static void Main()
    
    {
        Student std1 = new Student("Hinata ", "210111 ", "Database Management System 1", "DBMS 313 ", "Eastwoods Professional College of Science & Technology ", "BSIT ", 19);
        Student std2 = new Student("Matthew ", "210112 ", "Object Oriented Programming Language ", "OOPL 313 ", "Asia Pacific College ", "BSIT ",  21);
        Student std3 = new Student("Carmela ", "210113", "Integrative Programming Technology ", "IPT 313 ", "Bataan Peninsula State University ", "BSIT ", 20);
        Student std4 = new Student("Shoyo ", "210114 ", "Free Elective 1 ", "ITFE1 313 ", "Systems Technology Institute ", "BSIT ", 20);
        Student std5 = new Student("Eugene ", "21015 ", "College Physics ", "PHYS 313 ", "EPCST ", "BSCS ", 18);
        
        std1.info();
        std2.info();
        std3.info();
        std4.info();
        std5.info();
       
    }
}
