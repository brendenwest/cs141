=====
Intro to Programming
=====

**Reading**
* Building Java Programs, 1.1 - 1.3, 2.1


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

* human readable,
* easy to set up and run interactively,
* class-based & object oriented
* Open-source w/ large ecosystem of specialized libraries
 
**Running Java**

* local -v- cloud : Java can be installed and run on a local PC, or via a cloud-hosted service such as replit.com

**Java programs**

Java programs are composed of one or more commands contained in a plain text file saved with a .java extension.

The most basic Java program has a `main` method that is executed when the program runs.
::
    public static void main(String[] args) {
        System.out.println("Hello World");
    }


- program structure
- strings & escaping
- println
- errors
- identifiers
- reserved keywords


We'll cover more advanced commands throughout the course, but some basic commands you'll use:

* print text to the screen or log file.:
::
    System.out.println("Welcome")
    System.out.print("Welcome")

Note - by default, each *println* command prints a new line of text.:

* comments are not executed by the code interpreter and can take several forms:
::

    // this is a single-line comment

    System.out.println("Hello World"); // prints a greeting

    /*
    This is a multi-line comment
    that spans two lines
    */
