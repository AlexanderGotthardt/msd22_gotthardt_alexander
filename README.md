# Calculator-Example

**Calculator-Example** is an easy-to-use calculator designed to help with the first steps in test automation for use in education. The calculator takes two values and is able to perform basic arithmetic operations with it.

## Usage

To use this calculator application, follow these steps:

### Prerequisites

This application requires [Java](https://www.oracle.com/java/technologies/downloads/) to run.
>   Note: If you're not sure whether you have Java installed, you can open your terminal or command prompt and enter the following command:
    ```bash
    java -version
    ```
    If your terminal or command prompt returns a version number, you have Java installed. If the terminal or command prompt does not recognize the `javac` command, you must first [install Java](https://www.oracle.com/java/technologies/downloads/).

### Installation

1.  Download the folder containing the source files of the application from the [official download site](https://elearning.fh-joanneum.at/mod/resource/view.php?id=54031).

2.  Open your terminal or command prompt and navigate to the directory that contains the source files of the Java application (`CalculatorImpl.java` and `ICalculator.java`).

3.  Compile `ICalculator.java` by entering the following command:

    ```bash
    javac ICalculator.java
    ```

    This will create a compiled class file named `ICalculator.class`.

4.  Compile `CalculatorImpl.java` and include `ICalculator.class` in the classpath by entering the following command:

    ```bash
    javac -cp . CalculatorImpl.java
    ```

    This will create a compiled class file named `CalculatorImpl.class`.
    
### Run the application

Now that both Java source files have been compiled, you can run the application by entering the following command:
```bash
java CalculatorImpl.class
```

## Authorship

* Java application referenced in this README file courtesy of [Michael Ulm](https://www.michael-ulm.at) at the University of Applied Sciences FH JOANNEUM.

* Corresponding README file authored by Alexander Gotthardt.

### About the README author

My name is Alexander Gotthardt and I'm currently studying Mobile Software Development at the University of Applied Sciences FH JOANNEUM. I am currently trying to learn how to write README files and proper documentation.

## Other Markdown projects

| Project | README |
| ------ | ------ |
| Exercise 1 | [exercise1.md](./exercise1.md) |
| Exercise 2 | [exercise2.md]() |
| Exercise 3 | [exercise3.md]() |
| Exercise 4 | [exercise4.md]() |
| Exercise 5 | [exercise5.md]() |
| Exercise 6 | [exercise6.md]() |