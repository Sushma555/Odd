import java.util.Scanner;
class Odd 
{
public static void main(String[] args)
  {
Scanner sc = new Scanner(System.in);

System.out.println("Enter two digits separated only with spaces");

double a = input.nextDouble();
double b = input.nextDouble();
String oper = input.nextLine();
if(oper.equals(" add"))
   {
System.out.println("result= "+(a+b));
   }
else if(oper.equals(" sub"))
   {
System.out.println("result= "+(a-b));
   }
else if(oper.equals(" mul"))
   {
System.out.println("result= "+(a*b));
   }
else if(oper.equals(" div"))
   {
System.out.println("result= "+(a/b));
   }
else
   {
System.out.println(" invalid input");
   }
  }
}
