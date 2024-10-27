//Java_experiments
/*AIM:Write a program to add integer number and string using method overloading
 * NAME:KASHISH GUPTA 
 * UIN:231P081
 * ROLL NO:09*/
package pkg3;
class StrInt{
	public int add(int a,int b) {
		return a+b;
	}
	public String add(String a,String b) {
		return a+b;
	}
}
public abstract class AddNumberandStringMethodOverload {
	public static void main(String[] args) {
		System.out.println("~A PROJECT BY KASHISH GUPTA");
		StrInt obj=new StrInt();
		int sum=obj.add(5,10);
		System.out.println("Sum of integers:"+sum);
		String concatenatedString=obj.add("HELLO", "WORLD");
		System.out.println("Concatenated String:"+concatenatedString);
	}
}
