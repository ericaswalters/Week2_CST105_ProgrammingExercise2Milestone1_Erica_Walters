# Week2_CST105_ProgrammingExercise2Milestone1_Erica_Walters
/* This Program is my Week 2 Assignment
 * This program required the user to input their weight, and height in inches
 * This Formula uses a scanner for user input
 * This program is the sole and original work created by Erica Walters
 */

/** Program: Compute My BMI
 * File: ComputeMyBMI.java
 * Summary: Computes the user's body mass index based on the input data received for weight and height in inches.
 * Author: Erica Walters
 * Date: November 18, 2018
 */
import java.util.Scanner;

public class ComputeMyBMI {
    public static void main(String[] args) {
    // create Scanner
    Scanner input = new Scanner(System.in);
    
    //Enter weight
    System.out.print("Enter your weight in units of pounds ");
    double weight = input.nextDouble();
    
    //Enter heigt in units of inches
    System.out.print("Enter your height in units of inches i.e.: 4ft 2 inches is 50 ");
    double height = input.nextDouble();
    
    //Calculate BMI
    double BMI = (weight / (height * height)) * 703;
    
    //Display BMI
    System.out.println("Your BMI is " + BMI);
    }

}
