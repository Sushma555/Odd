import java.util.Scanner;
class Odd 
{
public static void main(String[] args)
  {
Scanner sc = new Scanner(System.in);

System.out.println("Enter the digit");

input n = sc.nextInt();
n = n*2;
for(int i=1; i<=n; i++)
   {
    if(i%2!=0)
   {
     System.out.println(i+" ");
   }
   }
     System.out.println();
  }
}
