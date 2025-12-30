experiment2
## Experiment2
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
#output
![experiment1 output](class mechanism.png)
