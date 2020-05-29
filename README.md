# How to create your first Java project with Eclipse IDE
Simple example of how to start programing with Java using the Eclipse IDE

## Definition
First JAVA project created with the Eclipse IDE

## Pre-requisites
- Java SE Installed
- Eclipse IDE Installed

## Java Installation (Windows)
1. Download Java SE from [here](https://www.oracle.com/java/technologies/javase-downloads.html).
2. Run the setup to install JAVA in your Local machine.
3. Configure the `PATH` and `CLASSPATH` Environment Variables.
4. Open a *Command Window* and run *javac -version*, if you get the version of your SRE, then Java was installed successfully.

## How to create, compile and run your program
1. Open a text editor, like Notepad, Notepad++, Sublime, Eclipse.
2. Copy next program

```java
public class myfirstclass {

	public static void main(String[] args) {
		System.out.println("This is my first code");
	}
  
}
```
3. Save the files as **myfirstclass.java**. We should always name the file same as the *public class* name.
4. Open Command prompt (cmd) on windows. 
5. Compile the program with the following command:

```java
javac myfirstclass.java
```
6. Now we can run the program, with next command:
```java
java myfirstclass
```

  If you get next error:
    Error: Could not find or load main class FirstJavaProgram
  then you can try with this command instead:
    
```java
java -cp . myfirstclass
```

