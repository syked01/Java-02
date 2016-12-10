# Java-02


===========================================

01. Square area

import java.util.Scanner;

public class ex01_Square_Area {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);
        
        System.out.print("a = ");
        int a = Integer.parseInt(console.nextLine());
        int area = a * a;
        System.out.println("area = "+ area);
    }
}

===========================================

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

03.Greeting

import java.util.Scanner;

public class ex03_Greeting {
    public static void main(String[] args){
        Scanner console = new Scanner(System.in);

        System.out.print("Enter your name : ");
        String name = console.nextLine();
        System.out.printf("Hello, %s!", name);
    }
}

===========================================

===========================================

04.Concatenate data

import java.util.Scanner;

public class ex04_Concatenate_Data {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);

        String firstName = console.nextLine();
        String lastName = console.nextLine();
        int age = Integer.parseInt(console.nextLine());
        String town = console.nextLine();
        System.out.printf("Your name is %s %s , %d years old , from %s.", firstName, lastName, age, town);
    }
}

===========================================