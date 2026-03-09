# JAVA-PROGRAM-TO-FIND-LARGEST-ELEMENT-IN-AN-ARRAY

## AIM:
To find the largest element in an array using java programming language.

## APPARATUS REQUIRED:

Computer 
Eclipse IDE

## THEORY:

Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let programmers write once, run anywhere (WORA), meaning that compiled Java code can run on all platforms that support Java without the needto recompile. Java applications are typically compiled to bytecode that can run on any Java virtual machine (JVM) regardless of the underlying computer architecture. The syntax of Java is similar to C and C++, but has fewer low-level facilities than either of them. The Java runtime provides dynamic capabilities (such as reflection and runtime code modification) that are typically not available in traditional compiled languages. As of 2019, Java was one of the most popular programming languages in use according to GitHub particularly for client–server web applications, with a reported 9 million developers.

## PROCEDURE:

Launch Eclipse IDE

o Open Eclipse.

o Select a workspace (folder for saving your projects).

Create a New Project

o Click File > New > Java Project

o Enter the project name.

o Click Finish.

Create a New Class 

o Right-click on your package → New > Class.

o Enter the class name (e.g., Main).

o Check public static void main(String[] args) (for Java).

o Click Finish.

Write Your Program

o Eclipse opens the code editor automatically.

o Type or paste your source code.

Save the Program

o Press Ctrl + S or click File > Save.

Compile and Run the Program

o Click the Run button (green ▶) on the toolbar.

o View output in the Console window.

Close Eclipse

o After finishing, click File > Exit to close Eclipse IDE.


## PROGRAM:
package dates;

import java.util.Scanner;

public class dates {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        // Input array size
        System.out.print("Enter the number of elements: ");
        int n = sc.nextInt();

        int[] arr = new int[n];

        // Input array elements
        System.out.println("Enter " + n + " numbers:");
        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
        }

        // Assume first element is the largest
        int largest = arr[0];

        // Compare with other elements
        for (int i = 1; i < n; i++) {
            if (arr[i] > largest) {
                largest = arr[i];
            }
        }

        // Output the result
        System.out.println("The largest element is: " + largest);

        sc.close();
    }
}


## OUTPUT:
<img width="400" height="100" alt="image" src="https://github.com/user-attachments/assets/198aeb64-cbde-4c2b-bdc5-3057bae81a1c" />


## RESULT:

Thus, the largest element in an array using java program is developed, and the output is verified.

