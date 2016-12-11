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

===========================================

05.Trapezoid area

import java.util.Scanner;

public class ex05_Trapezoid_Area {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);

        double b1 = Double.parseDouble(console.nextLine());
        double b2 = Double.parseDouble(console.nextLine());
        double h = Double.parseDouble(console.nextLine());
        double area = (b1 + b2) * h / 2;
        System.out.println("Trapezoid area = " + area);
    }
}

===========================================

===========================================

06.Area and perimeter of circle

import java.util.Scanner;

public class ex06_Area_And_Perimeter_Of_Circle {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);

        double r = Double.parseDouble(console.nextLine());
        double area = Math.PI * r * r;
        double perimeter = 2 * Math.PI * r;
        System.out.printf("Area = %f%nPerimeter = %f", area, perimeter);
    }
}

===========================================

===========================================

08. Triangle area

import java.util.Scanner;

public class ex08_Triangle_Area {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);

        double a = Double.parseDouble(console.nextLine());
        double h = Double.parseDouble(console.nextLine());
        double area = a * h / 2;
        System.out.printf("Triangle area = %.2f", area);
    }
}

===========================================

===========================================

09. Celsius to Fahrenheit

import java.util.Scanner;

public class ex09_Celsius_To_Fahrenheit {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);

        double cel = Double.parseDouble(console.nextLine());
        double far = cel * 1.8 + 32;
        System.out.printf("%.2f", far);
    }
}

===========================================

===========================================

10. Radians to degrees

import java.util.Scanner;

public class ex10_Radians_To_Degrees {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);

        double rad = Double.parseDouble(console.nextLine());
        double degr = rad * 180 / Math.PI;
        System.out.printf("%.0f", degr);
    }
}

===========================================

===========================================

11. USD to BGN

import java.util.Scanner;

public class ex11_USD_To_BGN {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);

        double usd = Double.parseDouble(console.nextLine());
        double bgn = usd * 1.79549;
        System.out.printf("%.2f", bgn);
    }
}

===========================================

===========================================