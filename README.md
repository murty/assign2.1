import java.util.Scanner;
class voting{
	public static void main(String args[]) {
	
int age;
System.out.println("enter age");
Scanner in = new Scanner(System.in);
age = in.nextInt();

if(age >=18)

System.out.println("you can vote");

else
System.out.println("you can not vote");


}
