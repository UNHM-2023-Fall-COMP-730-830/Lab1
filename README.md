# Lab1: Java Development Environment

In this first lab, we will
- install Eclipse Java IDE (Integrated Development Environment);
- add WindowBuilder to create a window application in 3 steps; and
- add SQLite JDBC drive to create a database application in 3 steps.

## Eclipse Java IDE
1. Go to <https://www.eclipse.org/downloads>.
2. Download an appropriate version of "Eclipse IDE 2023-03" (or the latest version).
3. Install Eclipse IDE by running the downloaded installer.

## Hello World

1. Run Eclipse IDE.
2. Choose an appropriate workspace directory and launch.
3. Kill the Welcome window by clicking X.
4. File -> New -> Java Project.
5. Set Project Name to "HelloWorld", uncheck "Create module-info.java file", and click on Finish.
6. File -> New -> Class, set Name to "HelloWorld", and click on Finish.
7. Add the following main method in the HelloWorld class definition.

        public static void main(String[] args) {
            System.out.println("Hello, world!");
        }

8. Execute the program by clicking the white triangle in the green circle.

    ![](doc_images/exec_symbol.png)

9. Click on OK in the "Save and Launch" window.
10. Check to see that "Hello, world!" is printed in Console.

Note 1: System.out.println() prints a string in one line in Console.

Note 2: Each Java program has to have one main method defined by `public static void main(String[] args) { ... }` in a class. 
This is the main method to be executed first when the Java program gets executed. 

Note 3: No specific requirements on the name of the class with the main method.

