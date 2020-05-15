# INSTRUCTION:

## Create a GitHub Account:

* Go to https://github.com and click `Sign up` for creating new GitHub account.

## Installation (Optional)

To simulate the student's role, I would advise you to install the following software:
1. `Git` --> https://git-scm.com/downloads
2. `Java` --> https://openjdk.java.net/install/
3. `Intellij IDEA` --> https://www.jetbrains.com/idea/download/

## Related YouTube Video:

1. [Git | How to install git on Windows](https://youtu.be/P1bh5qS63qQ)
1. [IntelliJ IDEA | How to clone, add, commit and push a repository to GitHub easily](https://youtu.be/RXV3Yusr0SI)
1. [GitHub | Creating a repository from a template](https://youtu.be/DKiS5qjfKho)


## Exercises (Will do these later thru Webex):

1. Create a new Java file called "HelloWorld". 
1. Create a new Java file called "HelloUum". 
1. Create a new Java file called "HelloQ1" in a `Question1` directory.


## Sample Java Codes:

1. This sample will be used to test the `output` of a Java program.
```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World"); 
    }
}
```

2. This sample will be used to test the `output` of __TWO(2)__ Java programs.
```java
class HelloUum {
    public static void main(String[] args) {
        System.out.println("Hello UUM Malaysia"); 
    }
}
```

3. This sample will be used to test the `output` of Java program in a `Question1` directory.
```java
package Question1;

class HelloQ1 {
    public static void main(String[] args) {
        System.out.println("Hello Q1"); 
    }
}
```

4. This sample will be used to test the `Input & output` of a Java program.
```java
import java.util.Scanner;

class HelloInput{

    public static void main(String[] args) {
        
        Scanner s = new Scanner(System.in);
        
        System.out.print("Please enter x: ");
        int x = s.nextInt();
        
        System.out.print("Please enter x: ");
        int y = s.nextInt();
        
        int z = x + y;
        System.out.println(z);
    }
}
```

## How to compile and run Java from command line (Optional)

1. For a single source file
```
$ javac HelloWorld.java
$ java HelloWorld
```

2. For a single source file in a `Question1` directory.
```
$ javac Question1/HelloWorld.java
$ java Question1/HelloWorld
```

## Git Command (Optional)

1. Create a new repository on the command line
```
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/azikri/test.git
git push -u origin master
```
2. Push an existing repository from the command line
```
git remote add origin https://github.com/azikri/test.git
git push -u origin master
```

