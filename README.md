package com.mph;

import java.util.Scanner;

public class PracExD1Q1 {

	public static void main(String[] args) {
		
		Scanner sc=new Scanner(System.in);
		
		int month=sc.nextInt();
		String mname="";
		
		switch(month)
		{
			case 1: mname="January";
				  break;	
			case 2: mname="February";
				  break;	
			case 3: mname="March";
				  break;	
			case 4: mname="April";
				  break;	
			case 5: mname="May";
				  break;	
			case 6: mname="June";
				  break;
			case 7: mname="July";
				  break;	
			case 8: mname="August";
				  break;	
			case 9: mname="September";
				  break;	
			case 10: mname="October";
				  break;	
			case 11: mname="November";
				  break;	
			case 12: mname="December";
				  break;		
			default: System.out.println("Invalid input");
				 System.exit(0);
		}
		System.out.println(mname);
	}

	

}

--------------------------------------
https://anotepad.com/notes/s6yqc76q
--------------------------------------------------------------------------
package com.mph;

import java.util.ArrayList;
import java.util.Arrays;
import java.util.List;
import java.util.stream.Collectors;

/*public class Test {
	public static void bufferReplace(StringBuffer text) {
		text.append("c");
		
	}
	public static void main(String args[]) {
		StringBuffer textBuffer=new StringBuffer("java");
		bufferReplace(textBuffer);
		System.out.println(textBuffer);
	}
}
*/
/*public class Test implements Runnable {
	int x,y;

	@Override
	public void run() {
		for(int i=0;i<10;i++) {
			//
			{
				x=12;
				y=12;
			}
		}
		System.out.println(x+""+y+"");
	}
	
	public static void main(String args[]) {
		//
	}
}

class Test implements Runnable{
	public static void main(String[] args) {
		Test t=new Test();
	
}


	@Override
	public void run() {
		// TODO Auto-generated method stub
		
	}
}


 class Test{
	public static void aMethod() throws Exception{
		try {
			int i=5/0;
			
		}finally 
		{
			System.out.println(" finally ");
		}
	}
	
	public static void main(String args[]) {
		try {
			int n=8/0;
		}catch(Exception e) {
			System.out.print(" exception ");
		}
		System.out.print(" finished");
	}
}


class Toy{
	private double price;
	private String color;

public Toy(String color, double price) {
	super();
	this.price = price;
	this.color = color;
}

public double getPrice() {
	return price;
}


public String getColor() {
	return color;
}

	
}

class Test{

	public static void main(String args[]) {
		List<Toy> toys=new ArrayList();
		toys.add(new Toy("red",10));
		toys.add(new Toy("yellow",30));
		toys.add(new Toy("red",10));
		
		double totalprice=toys.stream().filter(t -> t.getColor().equals("red")).mapToDouble(Toy::getPrice).sum();
				
				
			System.out.println("Total price of red toys"+totalprice);
		}
		
	}


class Test{
	public static void main(String args[]) {
		List strList;
		List<String> strings=Arrays.asList("Mumbai","Trichy","Delhi","Punjab","Banglore");
		List<String> s=strings.stream().filter(l -> l.length()==6).collect(Collectors.toList());
		System.out.println(s);
	}
}*/





class Test{
	public static void main(String args[]) {
		String s="Hello";
		System.out.println(alternatingChar(s));
	}
	public static String alternatingChar(String s) {
		StringBuffer sb=new StringBuffer();
		
		
	//	System.out.println("H"+"l"+"o");
		
		return sb.toString();
		}
}
