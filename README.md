# Java Hello World
This Java file contains the classic Hello World program in Java. Try tinkering with the code in the following ways to see what happens.

1. Change the class from `HelloWorld` to `helloworld`. Recompile. What happens? Change it back.
2. In the line containing `System.out.println("Hello, world!");`, try leaving out a quotation mark or the semi-colon. Recompile. What happens? Change it back.
3. Try manipulating the "Hello, World!" String to say something else. Recompile.
4. Based on your knowledge of programming, add the following line before the `System.out.println()`. `String name = "Sam";` Try to get the line to print out what the value of `name` is. Notice that in Java, we need to declare the types of variables.

## Get user input
1. Add the line `import java.util.Scanner;` above the HelloWorld class declaration. 
2. Add the following lines lines below `public static void main(String args[]) {`
```java
Scanner sc = new Scanner(System.in);
String name = sc.getNext();
sc.close();
```
Remove the line `String name = "Sam";`
