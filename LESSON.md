# Unit 1: Introduction to Programming & Setup

## Introduction
The entire unit lesson is located in this file.
Press `Ctrl` + `Shift` + `V` to open the *Preview*, which displays this file in the proper format (rather than the raw text).

<!---
If you see this sentence, you are not in Preview mode.
-->

At the top of the VS Code window is the *Tab Bar*, similar to what's in Google Chrome. You can use it to switch between previously opened files and delete unneeded ones.

### Table of Contents
- [Introduction](#introduction)
    - [Table of Contents](#table-of-contents)
- [Basic Java Program](#basic-java-program)
    - [Java Language Basics](#java-language-basics)
    - [> Exercise](#-exercise)
- [Recap](#recap)

## Basic Java Program
Welcome to your first Java program!
To start, we'll make your computer display, or **print**, `Hello World!`.

The code for this program is inside the `HelloWorld.java` file and has already been written for you. Let's open and run this file (but we won't edit it just yet). \
On the left menu column, make sure the *Explorer* (top button) is selected and is open. \
Then, in the *Explorer* side bar, click on `HelloWorld.java`.

> **Tip:** Press `Ctrl` + `Alt` + `RightArrow`, to split the current tab to the right side of the *Editor*. \
> This lets you view the Lesson and the Java program at the same time.

Don't worry if you don't understand any of the code in the file. \
To run our program, either click `Run` (appears between lines 1 and 2 in `HelloWorld.java`), or click the play icon in the *Tab Bar* (note that the `HelloWorld.java` tab must selected for the icon to appear).

Once you run it, a panel at the bottom will open as *Terminal*, and some text will appear. \
The second-to-last line of text is the program output, and it should say `Hello World!`. \
You got your computer to say hi!

### Java Language Basics
Like human languages, the Java programming language has grammar rules and punctuation. This is called **syntax**. \
Here's what you need to know for this unit:

- A **statement** is a single piece of code that instructs the computer to do one thing. It's akin to a sentence for English. A statement is typically on a single line. Note that in the `HelloWorld` program, only line 4 is a statement currently.
- A **semicolon `;`** is used to end a single statement. It's analogous to a period ending a sentence. *Don't forget to end every statement with a semicolon!*
- **Quotation marks `""`** are used to mark a **string**, which holds plain text that isn't Java code. For example, the `"Hello World"` string gets displayed to output by the program. Everything between the quotes is the string's text. When putting a string, don't forget the quotation marks, or else the computer will interpret the text as code to be executed and will get confused.
- `System.out.println(MESSAGE);` is a statement that prints `MESSAGE` to the output. \
`MESSAGE` must be a string, such as `"Team 1280"`.

Your code must follow syntax rules strictly; if you break them, the computer won't understand your program and it will show you an error message.

### > Exercise:
In `HelloWorld.java`, add a new statement between lines 4 and 5 that prints `Goodbye!`. \
Run the program. Expected output:
```
Hello World!
Goodbye!
```
<details><summary>Solution code</summary>

```java
class HelloWorld {
    public static void main(String[] args) {
        // Ignore everything above this line
        System.out.println("Hello World!");
        System.out.println("Goodbye!");
        // Ignore everything below this line
    }
}
```
</details>
<br>

> **Note:** Unlike other apps like Google Docs, VS Code *typically* won't automatically save your edits. You have to save them manually with `Ctrl` + `S`. \
> The one exception is that, when you run the Java program, edits to the file will get saved.

## Submitting This Assignment
When you make edits to a file tracked by Git, the changed lines and files will be highlighted.

(git extensions)
...

## Recap
In this unit, you learned:
- Basic navigation of VS Code
- How to run a Java program
- A bit of basic Java syntax
- How to print a message to the output
- 
