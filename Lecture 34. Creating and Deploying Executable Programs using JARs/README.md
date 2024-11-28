# Super Mario Bros Game Resources  

This repository contains resources and instructions to help students experiment with Java JAR files using the Super Mario Bros game. The goal is to aid in understanding the creation, extraction, and deployment of executable programs using JAR files in Java.  

---

## Getting Started  

### Prerequisites  
Ensure you have the following installed:  
- The latest version of Java (JRE or JDK).  
- A text editor or IDE (optional, for further exploration).  
- Git (optional, for cloning the repository).  

### How to Run the JAR File  
1. Download the `mario.jar` file from this repository or from the link below:  
   - [Super Mario Bros GitHub Repository](https://github.com/ahmetcandiroglu/Super-Mario-Bros)  
     *(Includes a JAR file: `1G.Super-Mario-Bros.jar` for experimentation)*  

2. Open a terminal or Command Prompt.  
3. Navigate to the directory containing the JAR file.  
4. Use the following command to extract or run the file:  
   ```bash
   jar -xvf mario.jar
   ```
   or  
   ```bash
   java -jar mario.jar
   ```  

---

## FAQ  

### Q1: How do I create and deploy programs using JAR files on Windows?  
**A:** The process for creating and deploying JAR files is the same across Windows, Linux, and macOS.  
- Open a terminal or Command Prompt.  
- Use the commands demonstrated in the lecture, such as:  
  ```bash
  jar -cf MyProgram.jar MyClass.class
  jar -xvf mario.jar
  ```  
If you need Windows-specific guidance, feel free to reach out!  

### Q2: The website mentioned in the lecture is not working. Where can I find the Mario game?  
**A:** Unfortunately, the website referenced in the lecture is no longer available. However, you can download similar versions of the Super Mario Bros game from GitHub:  
- [Super Mario Bros GitHub Repository](https://github.com/ahmetcandiroglu/Super-Mario-Bros)  
  *(Includes a JAR file: `1G.Super-Mario-Bros.jar`)*  
  Follow the documentation provided in the repository to play the game and test Java commands.  

### Q3: I get an error saying, "Please install the latest JRE," but I already have it installed. What should I do?  
**A:** This error may occur if the system can't locate the Java installation. Try these steps:  
1. Verify your Java version by running:  
   ```bash
   java -version
   ```  
2. Ensure Java is added to your system’s PATH environment variable.  
3. Run the JAR file explicitly using the command:  
   ```bash
   java -jar mario.jar
   ```  
4. If the problem persists, try using the JAR file provided in this repository or from the GitHub link above.  

---

## Credits  

- **Original Creators:** The versions of the Super Mario Bros game referenced are from GitHub users [ahmetcandiroglu](https://github.com/ahmetcandiroglu) and [pulkitcs21](https://github.com/pulkitcs21).  
- **Compiled by:** [Aswin Barath](https://github.com/AswinBarath), Teaching Assistant, Job Ready Programmer Team.  

---

## Notes  

- The goal of these resources is educational, focusing on understanding Java JAR file operations.  
- Some game versions are custom-built, and playing them might differ slightly. Refer to their documentation for detailed instructions.  

---

This README is ready for use! It combines all relevant details in an organized and professional manner. Let me know if you’d like any further edits!