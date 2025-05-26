# Unit 1: Introduction to Programming & Setup

## Introduction
The entire unit lesson is located in this file.
Press `Ctrl`+`Shift`+`V` to open the *Preview*, which displays this file in the proper format (rather than the raw text).

<!---
If you see this sentence, you are not in Preview mode.
-->

At the top of the VS Code window is the *Tab Bar*, similar to what's in Google Chrome. You can use it to switch between previously opened files and delete unneeded ones.

> **Note:** For Mac/Linux users: One of the extensions we had you install sets the VS Code keyboard shortcuts to Windows (instead of Mac or Linux). \
> This is to make shortcuts consistent across materials, and it makes it easier to use VS Code on Windows computers.

### Table of Contents
- [Introduction](#introduction)
    - [Table of Contents](#table-of-contents)
- [Basic Java Program](#basic-java-program)
    - [Java Language Basics](#java-language-basics)
    - [> Exercise](#-exercise)
- [Submitting Using Git](#submitting-using-git)
- [Recap](#recap)
    - [Keyboard Shortcuts](#keyboard-shortcuts)

[Feedback](#feedback) \
[License](#license)

## Basic Java Program
Welcome to your first Java program!
To start, we'll make your computer display, or **print**, `Hello World!`.

The code for this program is inside the `HelloWorld.java` file and has already been written for you. Let's open and run this file (but we won't edit it just yet). \
On the left menu column (called the *Activity Bar*), make sure the *Explorer* (top button) is selected and is open. \
Then, in the *Explorer* side bar, click on `HelloWorld.java`.

> **Tip:** Press `Ctrl`+`Alt`+`RightArrow`, or drag the the current tab (*Preview*) from the *Tab Bar* to the very right of the window. \
> This splits the current tab to the right side of the *Editor*, allowing you view the Lesson and the Java program at the same time.

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
- `System.out.println(VALUE);` is a statement that prints `VALUE` to the output. \
`VALUE` can be any value, such as the string `"Team 1280"`.

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

> **Note:** Unlike other apps like Google Docs, VS Code *typically* won't automatically save your edits. You have to save them manually with `Ctrl`+`S`. \
> The one exception is that, when you run the Java program, edits to the file will get saved.

## Submitting Using Git
To manage your files and version history across multiple *repositories*, programmers use Git. \
For training, we will also use Git to mark a unit as complete.

On the *Activity Bar*, click on *Source Control*, third from the top. Or press `Ctrl`+`Shift`+`G`. \
When you make edits to a file that Git tracks, the changes are highlighted, and you will see the file listed under *Changes*. You should see `HelloWorld.java` there. \
However, Git hasn't added your changes to the version history yet; you will need to *commit* them (save changes to version control). \
But first, you need to tell Git which changes you want to commit. (Sometimes, a programmer might want to commit only some of their changes.) \
Click on the `+` next to `HelloWorld.java` to *stage* the changes you made to this file, to prepare to commit them.

Every commit has a commit message, a description of the changes. This helps document the commit history. \
Click on the message box above *Commit* and type in a message like "Complete unit". \
Then, click *Commit* (or press `Ctrl`+`Enter`) to commit the staged changes.

> **Note:** Typically, it is best practice to make small and distinct commits instead of large commits with multiple unrelated changes. \
> For training, this is not necessary and you can do a single commit at the end of the unit.

This new commit currently lives on your computer only, in the *local repository*. \
For others to see your changes, you need to *push* your local commits to the *remote repository* at GitHub. \
The remote repository that you originally cloned with `Git: Clone`, and that you push changes to, is also called the *origin*. \
Click *Sync Changes* to push the commits to the GitHub repo, which also submits the assignment. In later units, mentors may give feedback on projects.

> **Note:** When the origin contains new commits (from a collaborator) that your local repository doesn't have, \
> you would *pull* the changes using *Sync Changes*.

## Recap
In this unit, you learned:
- Basic navigation of VS Code
- Running a Java program using `Run` button
- Basic Java syntax: statements, semicolons, strings
- Printing a message to the output using `System.out.println()`
- Using Git

### Keyboard Shortcuts
Throughout the course, various keyboard shortcuts will be mentioned. \
Don't memorize them, but instead simply try to **use only the ones that you find helpful**. \
There is a quicker keybinding for almost all operations, especially those where you'd typically use your mouse.

| Keybinding | Command |
| - | - |
| `Ctrl`+`Shift`+`V` | Open Preview of a *Markdown* (`.md`) file |
| `Ctrl`+`Alt`+`RightArrow` | Move current tab to split editor on right |
| `Ctrl`+`S` | Save edits to current file |
| `Ctrl`+`Shift`+`G` | Open *Source Control* |

## Feedback
Please provide feedback if you have any.

This is the first training with these new programming materials. \
We would appreciate if you mention any issues you had; you can also suggest improvements for them.
- Confusing explanations
- Knowledge, skills, or procedures that were required but weren't taught
- Too fast or too slow explanations; pacing
- Too hard or too easy exercises
- Step-by-step instructions that are not comprehensive/thorough enough, or didn't work
- Seemingly unnecessary or ineffective information or exercises
- Any improvements (e.g. wording) or more effective ways/formats to teach

Type below (go to the "raw" file, as *Preview* does not support editing). (For this unit, you need to make another commit):
___



## License
© 2025 @aatle, @spacepotatoes3

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
