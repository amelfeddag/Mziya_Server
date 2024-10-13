# Installation Guide

## Prerequisites
- **Java Version Required**: Make sure you have Java Development Kit (JDK) **version 11** or higher installed on your machine.
  - To check your Java version, run the following command in your terminal or command prompt:
    ```
    java -version
    ```
  - If you do not have Java installed, you can download it from [Oracle's official website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) or use an OpenJDK distribution like [AdoptOpenJDK](https://adoptopenjdk.net/).

## Steps to Run the JAR File
1. **Download the JAR file**:
   - Download the `HelloWorldApp.jar` file from the project repository or as provided by the client.

2. **Open your terminal or command prompt**.
   - Navigate to the directory where the `HelloWorldApp.jar` file is located using the `cd` command. For example:
     ```bash
     cd /path/to/HelloWorldApp.jar
     ```
    - Replace `/path/to/your/HelloWorldApp.jar` with the actual path on your computer where the JAR file is located.

3. **Run the JAR file**:
   - Use the following command to execute the JAR file in the console:
     ```bash
     java -jar HelloWorldApp.jar
     ```
    - Use the following command to execute the JAR file in the GUI: 
    ```bash
     java -jar HelloWorldApp.jar -GUI
     ```

4. **Verify the Output**:
   - You should see both the console output and a graphical user interface (GUI) displaying the "Hello World" message and the execution count.

## Troubleshooting
- If you encounter any errors related to Java, ensure that the correct version of the JDK is installed and that your system's environment variables are properly configured.
- If the GUI does not display, check that you have the required graphical libraries and dependencies installed on your system.
