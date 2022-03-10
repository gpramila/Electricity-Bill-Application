# EX 2 : Develop a Java application to generate Electricity bill
## AIM:

To develop a Java application to generate Electricity bill and Compute the bill amount using the following tariff.  

## EQUIPMENTS REQUIRED:

Eclipse 2021-03

## ALGORITHM:

Step 1: Start the program.

Step 2: Create a class Ebill with three member functions: getdata(), calc(), display() and object ob is created for another class Customerdata.

Step 3:Create another class Customerdata which defines the above functions.

Step 4: Using getdata() function get the consumed units for current and previous month . 

Step 5: Using calc()function calculate the amount depending on the type of EB connection and no. of units consumed.

Step 6: Using display() function display the bill. 

Step 7: Stop the program.

## PROGRAM:
```
import java.util.*; 
class Ebill 
{  
public static void main (String args[]) 
   {
      //Write your code here
    }
}

class Customerdata 
{ 
  	Scanner in = new Scanner(System.in);
  	Scanner ins = new Scanner(System.in); 
  	String cname; int bn; 
   double current,previous,tbill,units; 
   void getdata() 
 	{ 
      //Write your code here
  } 

   void calc()
 	{ 
        //Write your code here					
  	} 
  void display() 
   { 
        //Write your code here		
   	} 
} 
 





## OUTPUT
![Output](output.png)



## RESULT
Thus the java program to generate electricity bill was implemented, executed successfully and the output was verified. 
