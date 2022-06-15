# CircleStat

import java.util.Scanner;
public class CircleStat {
    public static void main (String[] args) {
    Scanner input = new Scanner(System.in);

    //input for the radius
    System.out.print("Enter the Radius: ");
    //declaring the variable of the radius
    double radius  = input.nextDouble();

    //Calculating the circumference
    double circumference= 2 * Math.PI *radius;

    //Calculating the area
    double area = Math.PI * radius * radius;

    //finishing and computing the message
    System.out.println("When the radius is " +radius+ "the circumference is" +circumference+"and the area is" +area+ ".");
    }
}
