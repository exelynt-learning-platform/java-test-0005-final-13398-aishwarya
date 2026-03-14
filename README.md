# java-test-0005-final-13398-aishwarya
Final Project Assignment - This repository contains the complete final project code and documentation.
public class FloydsTriangle {
    public static void main(String[] args) {
        int n = 5; // Number of rows to print
        int number = 1; // Starting number

        for (int i = 1; i <= n; i++) {
           
            for (int j = 1; j <= i; j++) {
                System.out.print(number + " ");
                number++; // Increment the number after printing
            }
           
            System.out.println();
        }
    }
}
