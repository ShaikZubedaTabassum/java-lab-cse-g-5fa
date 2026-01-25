#experiment
## 2a)Title:class mechanism in java
## Source code
``` java
class rectangle{
double length;
double breadth;
double area(){
return length*breadth;
 }
double perimeter(){
return 2*(length+breadth);
 }
}
class Main{
public static void main(String args[]){
rectangle rect=new rectangle();
rect.length=10;
rect.breadth=5;
double area=rect.area();
double perimeter=rect.perimeter();
System.out.println("area of given rectangle:" +area);
System.out.println("perimeter of given rectangle:" +perimeter);
  }
}
```
## output:
![experiment1 output](mechanism.png)
## Exp 2b) Title:implement method overloading
 ## Source code:
 ``` java
class sum{
int sum(int a,int b){
return a+b;
 }
int sum(int a,int b,int c){
return a+b+c;
 }
double sum(double a,double b){
return a+b;
  }
}
class main{
public static void main(String args[]){
sum s=new sum();
System.out.println("sum of 2 integers:" +s.sum(12,13));
System.out.println("sum of 3 integers:" +s.sum(12,13,14));
System.out.println("sum of 2 real numbers:" +s.sum(12-625,1-23));
  }
}
```
##output:
![experiment2 output](overlapping.png)
## Exp 2c) Title:to implement constuctor
## source code:
``` java
class student{
String sname;
int sage;
double smarks;
student(String name,int age,double marks){
sname=name;
sage=age;
smarks=marks;
}
void display(){
System.out.println("student name:" +sname);
System.out.println("student age:" +sage);
System.out.println("student marks:" +smarks);
  }
}
class main{
public static void main(String args[]){
student s=new student("zub",19,580);
s.display();
 }
}
```
##output:
![experiment2 output](constructor.png) 
```
