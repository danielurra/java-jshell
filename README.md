# Java JShell
![java-220x110px](https://github.com/danielurra/java-jshell/assets/51704179/34ad2576-5bfb-4b95-96e4-3675e4723886)

## JShell
Those of you who are new to Java programming, could take advantage of "JShell" which is often helpful for trying out the code snippets.<br>
JDK 9 and above include this tool that lets you execute a snippet of Java code instead of writing a full Java program.<br>
* For Beginners -> Practice and Learn the syntax
* For Developers -> Execute part of program in simple way
  
JShell is a `Read-Evaluate-Print-Loop` (**REPL**), which evaluates declarations, statements, and expressions as they are entered and immediately shows the 
results.<br>
## Why use JShell?
Jshell has reduced all the efforts that are required to run a Java program and test a business logic.<br>
If we don’t use Jshell, creating of Java program involves the following steps.<br>
* Open editor and write program
* Save the program
* Compile the program
* Edit if any compile time error
* Run the program
* Edit if any runtime error
* Repeat the process
  
Jshell does not require above steps. We can evaluate statements, methods and classes, even can write hello program without creating class.<br>
JShell helps you try out code and easily explore options as you develop your program.<br>
## Java version
```bash
java --version
```
![jshell-00](https://github.com/danielurra/java/assets/51704179/d18fbe3a-35ac-4088-a9c7-fca64626d53d)
## Launch JShell
```bash
jshell
```
![jshell-01](https://github.com/danielurra/java/assets/51704179/45345190-7348-4e1d-8361-ad5883d8442f)
## Eexecute your first Java snippet of code
**No semicolons needed**</br>
```bash
System.out.println("Hello JDK 19!")
```
![jshell-02](https://github.com/danielurra/java/assets/51704179/39fbe7de-e7a1-46c3-b2bc-63f6941b2d1c)
## Biggest Integer possible with 32 bits
```bash
jshell> int biggestInt = 3;
biggestInt ==> 3

jshell> biggestInt = Integer.MAX_VALUE;
biggestInt ==> 2147483647
```
![biggest-integer-v2](https://github.com/danielurra/java-jshell/assets/51704179/bb498d1f-4c11-46e6-aeda-00a5aeb1b369)

## Seeing documentation
Use the `TAB` key of your keyboard **twice** to see the built-in documentation
![jshell-use-TAB-to-see-signatures-documentation](https://github.com/danielurra/java/assets/51704179/f9c5ecfa-1b8f-4e6c-b435-f37ad04a7686)

## Exit JShell
```bash
/exit
```
![jshell-03](https://github.com/danielurra/java/assets/51704179/0370a258-e7b6-4354-9803-76bab3890759)
