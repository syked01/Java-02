# Java-02


===========================================

02.Inches to centimeters

import java.util.Scanner;

public class ex02_Inches_To_Centimeters {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);

        System.out.print("Inches : ");
        double inches = Double.parseDouble(console.nextLine());
        double cm = inches * 2.54;
        System.out.println("Centimeters : " + cm);
    }
}

===========================================

===========================================