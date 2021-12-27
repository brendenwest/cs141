=====
Intro to Programming
=====

**Reading**
* Building Java Programs, Ch. 1.1 - 1.3

**Summary**

* Class overview
* What is computer science?
* Computer programming overview
* Programming languages overview
* Running Java
 
**What is computer science?**

* Design, Analysis, Experimentation
* **Design** is the process of creating an algorithm - a step-by-step process for solving a problem with computation
* **Analysis** is the process of examining algorithms & problems mathematically
* **Experimentation** is the process of testing a system for possible solutions or verifying that a solution works
 
**What are programs?**

* Programs (software) are step-by-step instructions telling a computer what to do
* Programs are ‘executed’ by the computer
* Programming is the art of writing programs, and a fundamental part of computer science
* Also a form of expression. Programming can be fun.
 
**Computer hardware terms**

* CPU - central processing unit carries out all basic data operations
* GPU - graphics processing unit. Similar to CPU, but optimized for operations typical for graphics
* Memory - stores programs and data
* Main memory (RAM) is fast, but volatile
* Secondary memory - persistent but slower than RAM
* Input - How information is passed to the computer. E.g. keyboard, mouse, etc
* Output - How information is presented to the user - e.g. monitor, printer

**Programming languages**

* Unambiguous way of providing instructions to a computer
* High level -v- low level
  - High-level languages are designed to be understood by humans. E.g. Python, Java, C++
  - Low-level languages optimized for machines - Machine code, Assembly
* Compilers convert code from a high-level language to machine-specific code (binary). Compiled languages include Java, C++, C#
* Interpreters allow a computer to execute high-level code without advance compilation. Interpret languages include Python, JavaScript
* Compiled programs generally runs faster than interpreted code
* Interpreted code can be developed and run interactively

**Why Java?**

* high-performance
* Widely used for application development
* class-based & object oriented
* Open-source w/ large ecosystem of specialized libraries
 
Running Java
----

* local -v- cloud : Java can be installed and run on a local PC, or via a cloud-hosted service such as https://replit.com

**Java programs**

Java programs are composed of one or more commands contained in a plain text file saved with a .java extension.

The most basic Java program has a `main` method, contained within a 'class', that is executed when the program runs.
::
    public class Hello {
        public static void main(String[] args) {
            System.out.println("Hello World");
        }
    }

We'll cover classes and methods in more detail later. For now note a few Java rules:

- class names are capitalized
- code for a class or method is contained within curly brackets
- commands end with a semi-colon
- indenting is optional but helps with reading the code

The .java file must be **compiled** before it can be executed.


We'll cover more advanced commands throughout the course, but some basic commands you'll use:

Print text to the screen or log file.:
::
    System.out.println("Welcome");
    System.out.print("Welcome");

By default, each *println* command prints a new line of text.

**comments** are not executed by the code interpreter and can take several forms:
::

    // this is a single-line comment

    System.out.println("Hello World"); // prints a greeting

    /*
    This is a multi-line comment
    that spans two lines
    */

**Strings**

Literal sequence of characters delimited by double quotes.

Double-quotes inside the string must be *escaped* with a backslash.
::
    System.out.println("tonight's episode of \"Game of Thrones\" was awesome");

Strings can contain **control** characters - e.g. tab or new-line:
::
    System.out.println("this should print \n on two lines");

Strings can be combined (**concatenated**) with a plus sign:
::
    System.out.println("this " + "and that");

Strings can be concatenated with non-string values into a new string:
::
    System.out.println("Happy New Year " + 2022 + "!");

**Identifiers**

Names for parts of a Java program must follow certain rules:

- must start with a letter
- can contain any number of letters or digits
- cannot contain special characters (e.g. punctuation) or spaces
- usually lower-case, except for class names
- cannot be a **reserved** word that has meaning in Java

Terms
____

* class - a basic, re-usable unit of code
* comment - explanatory text ignored by the compiler
* compiler - a program that translates other programs from one language (usually higher-level) to another (usually machine-specific)
* data type - name for a category of data values
* identifier - name given to a program entity, e.g. a class or method
* method - a program unit for a particular action or computation
* program - a list of instructions to be carried out by the computer
* statement - code that represents a single, complete command
* string - a sequence of characters delimited by double quotes
