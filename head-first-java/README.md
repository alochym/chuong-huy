# Head First Java

1. Java write-once/run-anywhere.
1. How it works

```bash
Source (.java ext) > Compiler (javac) > output bytecode (.class ext) > Java Virtual Machine (JVM - java).
```

1. JDK - Java Developer Kits.
1. JRE - Java Runtime Enviroment.
1. JVM - Java Virtual Machine.
1. <https://www.ibm.com/cloud/blog/jvm-vs-jre-vs-jdk>

## Code struture in Java

```bash
|----------------------|       |-------------------------| 
|                      |       |                         |
|     Source file      |       |        Dog.java         |
|                      |       |                         |
| |------------------| |       | |---------------------| |
| |                  | |       | |                     | |
| | Class Definition | |       | | public class Dog {  | | 
| |                  | |       | |                     | |
| |------------------| |       | |---------------------| |
| |                  | |       | |                     | |
| | |------------|   | |       | | |---------------|   | |
| | | Method 1   |   | |  ==>  | | | void bark() { |   | |
| | | statements |   | |       | | |   statements; |   | |
| | |            |   | |       | | | }             |   | |
| | |------------|   | |       | | |---------------|   | |
| |                  | |       | |                     | |
| | |------------|   | |       | | |---------------|   | |
| | | Method 2   |   | |       | | | void walk() { |   | |
| | | statements |   | |       | | |   statements; |   | |
| | |            |   | |       | | | }             |   | |
| | |------------|   | |       | | |---------------|   | |
| |                  | |       | |                     | |
| |                  | |       | | }                   | |
| |------------------| |       | |---------------------| |
|----------------------|       |-------------------------|
```

### Quick start

1. Create an alochym.java file.

   ```java
   public class alochym {
       public static void main(String[] args) {
           System.out.println("I Rule!!!");
           System.out.println("The World");
       }
   }
   ```

1. Compile a source code alochym.java file into alochym.class file - javac alochym.java
1. Execute an alochym.class file - java alochym
