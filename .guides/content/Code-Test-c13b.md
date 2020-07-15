----------

## Standard Code Test

Write a program that takes an integer from the user. Return the number multiplied by three. If the user enters a non-integer data type, return the following message:

`Please enter an integer`

{Try it | terminal}(sh .guides/bg.sh javac code/Test.java java -cp code/ Test )

<table><tbody ><tr><td><details><summary>
    <strong>Solution</strong>
</summary>

Here is one solution to the problem. You can copy/paste it into the IDE if you would like.

```java
    Scanner input = new Scanner(System.in);
    
    if(input.hasNextInt()) {
      int num = input.nextInt();
      System.out.println(num*3);
    }
    else { System.out.println("Please enter an integer"); }
```


    
</details></td></tr></tbody>
</table>

{Check It!|assessment}(code-output-compare-4266318069)