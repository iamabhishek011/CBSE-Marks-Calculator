# CBSE-Marks-Calculator
Write a program to calculate the percentage of a given student in the CBSE board exam. His marks from 5 subjects must be taken as input from the keyboard. (Marks are out of 100)

import java.util.Scanner;
public class Main{
    public static void main(String []args){
        Scanner sc = new Scanner(System.in);
        System.out.println("Welcome to the CBSE Marks Calculator");
        System.out.println("Enter your Marks in Physics");
        float physics = sc.nextFloat();
        System.out.println("The marks in Physics: " +physics);
        System.out.println("Enter your Marks in Chemistry");
        float chemistry = sc.nextFloat();
        System.out.println("The marks in Chemistry: " +chemistry);
        System.out.println("Enter your Marks in Biology");
        float biology = sc.nextFloat();
        System.out.println("The marks in Biology: " +biology);
        System.out.println("Enter your Marks in Mathematics");
        float mathematics = sc.nextFloat();
        System.out.println("The marks in Physics: " +mathematics);
        System.out.println("Enter your Marks in Bengali");
        float bengali = sc.nextFloat();
        System.out.println("The marks in Physics: " +bengali);
        float sum = (physics+chemistry+biology+mathematics+bengali);
        float percentage = (sum*100)/500;
        System.out.println("The Percentage is: " +percentage);
    }
}
