# Advanced-Java
This repository provides solutions for college-level advanced Java programs.

# Running a Java Program in GitHub Codespaces

## Setting Up the Environment

1. **Open GitHub Codespace:**
   - Navigate to your repository on GitHub.
   - Click on the `Code` button and then the `Codespaces` tab.
   - Click on `Create codespace on main` (or your chosen branch).

2. **Update Package List:**
   ```sh
   sudo apt update

3. Install OpenJDK 11:
    Install OpenJDK 11 by running:
   ```
   sudo apt install openjdk-11-jdk -y

4. Verify Java Installation:
 Ensure Java is installed correctly by checking the version:
```
java -version
```
5.  Create Your Java Program:
   Inside your Codespace, create a new Java file named HelloWorld.java:
```
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
6. Compile the Java Program:
   In the terminal, compile your Java program using javac:
   ```javac HelloWorld.java ```

7.Run the Java Program:
After compilation, run the program using java:
``` java HelloWorld```


