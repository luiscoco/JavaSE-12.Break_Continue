# JavaSE-Break Continue

In Java, break and continue are control flow statements used within loops (such as for or while) to alter the normal flow of execution.

## 1. break statement
The break statement is used to terminate the loop prematurely. When encountered, it immediately exits the loop, and the control is transferred to the statement following the loop.

Example: Using break in a for loop:

```java
for (int i = 1; i <= 10; i++) {
    System.out.println(i);
    if (i == 5) {
        break; // exit the loop when i becomes 5
    }
}
```

In this example, the loop will print numbers from 1 to 5 and then exit because of the break statement.

## 2. continue statement
The continue statement is used to skip the rest of the code inside the loop for the current iteration and move to the next iteration.

Example: Using continue in a for loop:

```java
for (int i = 1; i <= 5; i++) {
    if (i == 3) {
        continue; // skip the rest of the loop body for i=3
    }
    System.out.println(i);
}
```

In this example, when i is 3, the continue statement is encountered, and the loop skips printing 3. It then continues with the next iteration.

```
Output:
1
2
4
5
```

I hope this clarifies how break and continue work in Java loops! If you have any more questions or if there's something specific you'd like to know, feel free to ask.
