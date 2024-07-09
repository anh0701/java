# About Java language

- [Data Types and Variables](#1-data-types-and-variables)
    - [Data type](#11-data-types)
    - [Variables](#12-variables)
    - [Rules for naming variable](#13-rules-for-naming-variable)
    - [Literals](#14-literals)

- [Features and Architecture](#2-features-and-architecture)
    - [Compiler vs Interpreter](#21-compiler-vs-interpreter)
    - [Java is Platform Independent](#22-java-is-platform-independent)
    - [JVM Architecture](#23-jvm-architecture)
    - [Features of Java](#24-feature-of-java)


## 1. Data Types and Variables 

### 1.1 Data types 

- Primitive Data Type: boolean, char, int, short, byte, long, float, double

- Non-Primitive Data Type or Object Data Type: String, Array, ...

```
    Data Types in Java
    |
    ├── Primitive Data Types    
    │   ├── Non Numeric Type
    │   │   ├── boolean (8 bits)
    │   │   └── char (16 bits)
    │   └── Numeric Type
    │       ├── Integer
    |       |   ├── byte (8 bits)
    |       |   ├── short (16 bits)
    |       |   ├── int (32 bits)
    |       |   └── long (64 bits)
    │       └── Floating Point
    |           ├── float (32 bits)
    |           └── double (64 bits)
    └── Non-Primitives Types
        ├── String (an array of characters)
        ├── Array (groups of like-types variables)
        ├── Class (user-defined blueprint or prototype from which object: modifiers, class name, super class if any, interfaces if any, body)
        ├── Object (basic unit of Object-Oriented, An object consists of : state, behavior, identity)
        └── Interface (have methods and variables: only method signature, no body)

```

### 1.2 Variables 

- is a name given to a memory location. 
- is the basic unit of storage in a program.
- the value stored in a variable can be changed during program execution.
- all the operations done on the variable affect that memory location.
- all variables must be declared before use.
- declare variables: 
    ```java 
        datatype data_name;
        // datatype: type of data that can be stored in this variable
        // data_name: name was given to the variable

        int time;
        float price;
        char var;
    ```
- initialize variables:
    ```java
        datatype variable_name value;
        // datatype: type of data that can be stored in this variable
        // variable_name: name was given to the variable
        // value: the initial value stored in the variable
        int time = 10;
        char var = 'a';
    ```
- Types of variables 
    - local variable
    - instance variable
    - static variable

    ```
        Type of variable
        ├── local variables
        |   ├── are created when the block is entered, or the function is called
        |   ├── are destroyed after exiting from the block or when the call returns from the function.
        |   ├── the scope of variables exists only within the block in which the variables are declared 
        |   └── Initialization of the local variable is mandatory before using it in the defined scope
        ├── instance variables
        |   ├── 
        |   ├──
        |   └── 
        └── Static variables
            ├── 
            └── 
    ```
### 1.3 Rules for naming variable

### 1.4 Literals

## 2. Features and Architecture

### 2.1 Compiler vs Interpreter

### 2.2 Java is Platform Independent

### 2.3 JVM Architecture

### 2.4 Feature of Java
