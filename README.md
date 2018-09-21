# Seriously
String exercise
package stringAssignments;

import java.util.Scanner;

public class Seriously {
	public static void main(String[] args) {

		Scanner input = new Scanner(System.in);
		System.out.println("Enter please any word");
		String anyword = input.next();

		if (anyword.endsWith("ly") == true) {
			System.out.println("Really?");
		} else {
			System.out.println("never mind");
		}
		input.close();
	}
}
