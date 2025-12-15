
# Java 21 + IntelliJ Setup (Quick Start)

> Goal: Be ready to **run a Java file in IntelliJ** (and try `jshell`) before the next session.

---

## 1) Install JDK **21** (Long-Term Support)

Choose **one** vendor (both are fine):

- **Eclipse Adoptium Temurin 21 (LTS)** – cross‑platform builds.  
  Download: https://adoptium.net/temurin/releases/?version=21

- **Oracle JDK 21 (LTS)** – official Oracle builds.  
  Download: https://www.oracle.com/java/technologies/downloads/#jdk21

### Verify your install (all platforms)
Open a terminal / command prompt and run:
```bash
java -version
javac -version
jshell --version
```
Expected: all three commands print **21.x**

> If you see “command not found”, re-open the terminal after install. On Windows, ensure the installer added Java to PATH.

---

## 2) Install **IntelliJ IDEA**

- Official download page: https://www.jetbrains.com/idea/download/
- Starting with **IntelliJ IDEA 2025.3**, JetBrains is moving to a **unified installer** (single distribution). The free core is enough for this course.

### First run (create a plain Java project)
1. **New Project → Java**, set **SDK = JDK 21**, Finish.
2. In `src`, create class **App** and paste:
   ```java
   public class App {
     public static void main(String[] args) {
       System.out.println("First run OK");
     }
   }
   ```
3. Click the green **▶** next to `main` or in the gutter.

> If IntelliJ can’t find the JDK: **File → Project Structure → SDKs → Add JDK** and point it to your JDK 21 folder.

---

## 3) JShell

Try quick experiments without a project:
```bash
jshell
jshell> System.out.println("Hi");
jshell> int a = 10; long b = 20L; a + b
```


AS Per Topics of First lecture 
Go through following questions :
1. What is language ?
2. Explain language and its types in brief or detais?
3. What is programming language ?
4. How person can communicate with each other ?
5. How does person tell computer to program to perform task ?
6. Can person tell to perform task and can computer do pre-defined task or have the set of task to perform ?
7. Explain Human to Human communication and Human to Machine Communication in brief with the help of neat labelled diagram and example?
8. Why Grammaer is used in language and notations are used in grammer?
9. Explain History from Human language to High level language with diagram and examples?
10. Which are components of programming language?
11. Explain types of components of code in detailed with the help of real time examples ?
12. What is syntax , explain in brief ?
13. What is difference between H2H and H2M ?
14. What is difference between Syntatically and Sematically components?
15. Why Computer science is developed, Explain with diagram with great example?
16. Why Programming languages are cultivated in the land of Earth technology ?
17. Give reason Why you want to be a Proggramer of life of technologies of Robots?
18. Give reason Why there is need to do study of technology?
19. Give reason Why we cannot do activities of daily life in technological way of computer science ?
20. What is history of programming?
21. What is java?
22. Why java why not other language?
23. What is OOPs ?
