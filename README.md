## INSTRUCTION:

1. Create a new Java file called "HelloWorld". 
1. Create a new Java file called "HelloUum". 
1. Create a new Java file called "HelloQ1" in a `Question1` directory.


## Sample Java Codes:

1. This sample will be used to test the `output` of Java program.
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


## How to compile and run Java from command line

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

