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
