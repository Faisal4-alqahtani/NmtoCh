NmtoCh
package Nmofch;
import java.util.Scanner;
public class NmofCh {
public static void Three() {
	System.out.println("Act");
System.out.println("Ads");
System.out.println("And");
System.out.println("Art");
System.out.println("Ask");
System.out.println("Fix");
System.out.println("Fly");
System.out.println("Few");

}
	public static void main(String[] args) {
		// TODO Auto-generated method stub
Scanner reader = new Scanner(System.in);
System.out.print("How many letters do you want in a word?");
int letters = 0 ;
letters=(int) reader.nextDouble();
if(letters <= 2)
	System.out.println("There is no word for the number of letters");
else if(letters == 3)
	Three();
else if(letters == 4)
	System.out.println("care" + " " + "dead" + " " + "earn" + " " + "fear" + " " + "give" + " " + " boss" + " " + "abel" + " " + "away");
else if(letters == 5)
	System.out.println("alert" + " " + "allow" + " " + "argue" + " " + "aware" + " " + " photo");
else
	System.out.println("I’m sorry , You have to search for yourself " + " " + "I am programmed for five letters only"); 

	
	}
