# javacode
import java.util.*;
import java.util.Scanner;

public class snapchat {
	String id;
	String password;
	public snapchat(String id,String password) {
		// TODO Auto-generated constructor stub
		this.id=id;
		this.password=password;	
	}
	public void login(String i,String p ) {
		if (i==id && p==password)
			System.out.println("Login successfull");
		else 
			System.out.println("Invalid data");	
	}
    public static void main(String args[]) {
    	Scanner sc=new Scanner(System.in);
		System.out.println("enter i");
		String i=sc.next();
		System.out.println("enter p");
		String p=sc.next();
		snapchat s=new snapchat("sonu5","sweety8");
            s.login(i,p);
    }
    
		
}
