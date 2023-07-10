![Kotlin.png](../img/Kotlin.png)

# Java Virtual Machines (JVM) and Kotlin

Kotlin code is compiled into JVM (Java Virtual Machine) bytecode, so Kotlin can be used almost anywhere Java can be used. Kotlin code is 100% compatible with Java, meaning it can use existing Java libraries. If you're working on an application with a large amount of legacy Java code, you don't have to abandon all the old code - the new Kotlin code will work alongside it. And if you want to use Kotlin code written from Java code - that's also possible without any problems.

# Android

Alongside other languages (like Java), Kotlin has full Android support. Kotlin is fully supported by Android Studio.

# Client-side and Server-side JavaScript

Kotlin code can also be transpiled (that is, translated into another language) into JavaScript, and you can execute it in the browser. In particular, this allows you to use various technologies on the client side and server side, such as WebGL or Node.js

# Your First Kotlin Project

#### Anatomy of a main function

Our Kotlin code should print the message "Pow!" in the IDE output window. To do this, we will add a function to the App.kt file.

```kotlin
/*
*   "fun" means that this is a function
* 
*   main is the function's name
*
*   (args: Array<String>) The function's parameters, enclosed in parentheses. The function receives
*   an array named "args" which contains string elements.
*
*   { } The function's opening and closing brace.
*
*   The println("Pow!") call directs a string of characters (String) to the standard output.
* 
* */


fun main(args: Array<String>) {
    println("Pow!")
}
```

The function starts with the keyword fun, which tells the compiler that this is a function declaration. The keyword fun should always be used when you create a new function. Following the keyword fun is the function's name - in this case main. The function named main will automatically run when the application is launched. The code in parentheses () after the function's name tells the compiler what arguments the function receives (if it receives any at all). In this case, the code args: Array<String> means that the function receives an array of strings, and this array is named args. All the code that you want to execute is enclosed in the braces {} of the main function. We want the function to print the message "Pow!" in the IDE.
