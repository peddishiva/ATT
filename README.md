# ATT
This repo has the program codes of MY ATT Lab i.e (Automated testing tools)

### 12 weeks plan to focused on learning automation testing using **Selenium Grid**, **Eclipse IDE for Java**, and **ChromeDriver**. let's see the installation process and Then Dive into the plan
---

# Installation Guides
### Installation of **JAVA** **Selenium Grid**, **Eclipse IDE for Java**, and **ChromeDriver**.

### 1. Install Java Programming Language

1. Go to the official Oracle JDK download page:  
   [https://www.oracle.com/java/technologies/javase-jdk11-downloads.html](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)  
   *(You can choose the latest version or LTS like JDK 11)*

2. Select your OS (Windows/Mac/Linux) and download the installer.

3. Run the installer and follow the on-screen instructions to complete installation.

4. Set the **JAVA_HOME** environment variable:  
   - On Windows:  
     - Open System Properties > Advanced > Environment Variables  
     - Create a new system variable `JAVA_HOME` pointing to the JDK installation folder (e.g., `C:\Program Files\Java\jdk-11.0.12`)  
     - Add `%JAVA_HOME%\bin` to the `Path` variable.

5. Verify installation:   Open Command Prompt and type:  

   java -version
   
   It should display the installed Java version.
   
---

### 2. Download and Setup Selenium Grid

1. Go to the official Selenium downloads page:  
[https://www.selenium.dev/downloads/](https://www.selenium.dev/downloads/)

2. Scroll to **Selenium Server (Grid)** section and download the latest Selenium Server standalone `.jar` file.

3. Place the `.jar` file in a convenient folder (e.g., `C:\selenium\`).

4. To start the Selenium Grid Hub, open Command Prompt and run:

    java -jar selenium-server-<version>.jar hub

5. To register nodes (browsers), run:

   java -jar selenium-server-<version>.jar node --hub http://localhost:4444
   
---

### 3. Download ChromeDriver

1. Check your installed Chrome browser version:  
Open Chrome > Menu > Help > About Google Chrome.

2. Go to ChromeDriver downloads:  
[https://sites.google.com/chromium.org/driver/](https://sites.google.com/chromium.org/driver/)

3. Download the ChromeDriver version matching your Chrome browser version.

4. Extract the downloaded zip file and place the `chromedriver.exe` file in a folder, e.g., `C:\drivers\`.

5. Add the folder path (`C:\drivers\`) to your system `Path` environment variable.

6. Verify installation by running in Command Prompt:

   chromedriver --version

---

### 4. Download and Install Eclipse IDE for Java Developers

1. Go to the Eclipse official download page:  
[https://www.eclipse.org/downloads/](https://www.eclipse.org/downloads/)

2. Download **Eclipse IDE for Java Developers** for your OS.

3. Extract the downloaded package and run the `eclipse.exe` (Windows) or the corresponding launcher for your OS.

4. Follow the setup wizard and select your workspace location.

5. Eclipse IDE is now ready for Java development and Selenium automation projects.

---
# 12-Week Automation Testing & Tools Learning Plan

This plan is focused on learning automation testing using **Selenium Grid**, **Eclipse IDE for Java**, and **ChromeDriver**.
---
### Week 1  
- Download and install Java  
- Download Associate SWD JAR files and browser drivers  

### Week 2  
- Launch Mercury Tours website  
  - a) Click on Register link to open registration page  
  - b) Fill the registration fields  
  - c) Click Submit  
  - d) Close the site  

### Week 3  
- Write code to search for a specific month in Facebook registration page's Birthday field  

### Week 4  
- Write a program to pop up an alert message inside a frame on a personal banking login page  

### Week 5  
- Write a test case to search the result section on the CMRIT website  

### Week 6  
- Write a test case to perform automation on the Ajio shopping website  

### Week 7  
- Write a WebDriver program to open Google and search for "CMRIT"  

### Week 8  
- Write a test case to open Google and download an image from Google Images related to the CMRIT website  

### Week 9  
- Write a test case to get the number of list items in a list  

### Week 10  
- Write a test case for form validation on Gmail registration page  

### Week 11  
- Write a test case for Myntra sign-in page  

### Week 12  
- Write a test case to convert PDF from a Word document  

---

This plan progressively builds automation skills with real-world test cases and practice using Selenium Grid and ChromeDriver within Eclipse IDE.

