## 🚀 Selenium Automation - Implementing Log4j2 for logging :
Excited to share my recent experience enhancing my Selenium automation framework by integrating **Log4j2** for logging! Logging is a key part of any test automation framework—it helps track each step of execution, simplifies debugging, and provides clear insights during test runs. This project showcases how I implemented logging in a **Selenium + Java + TestNG** framework using Log4j2.

---

### 🛠️ Tools and Technologies Used

| Category             | Tools / Technologies                             |
|----------------------|--------------------------------------------------|
| **Programming**      | Java                                             |
| **Build Tool**       | Maven                                            |
| **Testing Framework**| TestNG                                           |
| **Automation Tool**  | Selenium WebDriver                               |
| **Logging Framework**| Log4j2                                           |
| **Design Pattern**   | Page Object Model (POM)                          |
| **Dependency Manager** | Maven `pom.xml`                                 |
| **IDE**              | Eclipse                                          |
| **Version Control**  | Git & GitHub                                     |
| **Configuration**    | `QA-config.properties`, `log4j2.properties`      |

---

## 🔍 Benefits of Using Log4j2 in This Framework
- ✅ Clear visibility of WebDriver actions and test steps
- 🐞 Quick identification of issues with stack traces in logs
- 🔁 Easier debugging of flaky or intermittent test failures
- 📂 Logging output saved to both console and log files
---

### Project Structure:  
<img width="312" alt="" src="https://github.com/user-attachments/assets/bdc87662-9b7d-455d-9967-cc530f69c140" />

---

### Implementation Highlights:
1. Added Log4j2 Dependencies to pom.xml
   <br>
   <img width="1000" alt="" src="https://github.com/user-attachments/assets/34bc470c-666e-4f6c-9615-cd4968f225c2" />  
   <br>
2. Created log4j2.properties in src/test/resources    
   <br>
   <img width="1034" alt="" src="https://github.com/user-attachments/assets/7901ab7d-e07f-445b-acb3-db0016d55afe" />  

4. Utilized Log4j2 in BaseTest, DriverFactory class, and pages classes for logging browser actions, test steps, and exceptions.
   <br>  
   🔹**BaseTest.java**
   <img width="1001" alt="" src="https://github.com/user-attachments/assets/62962e88-758d-441f-a4bf-2d77885c7098" />
   <br>  
   🔹**DriverManager.java**
   <img width="1094" alt="" src="https://github.com/user-attachments/assets/dcd394a8-2fe5-4fbd-9701-f68b0895b505" />
   <br>  
   🔹**LoginPage.java**
   <img width="1034" alt="" src="https://github.com/user-attachments/assets/f937d99a-6d0f-4193-9171-5127d7ba6c73" />
   <br>  
   🔹**ProductsPage.java**
   <img width="1034" alt="" src="https://github.com/user-attachments/assets/4240888a-5a4e-416d-b843-4c7d5232b500" />  

---

### ▶️ Steps To Run:
1. Create and Clone the project to selenium-automation-logging-using-log4j2 folder
```
git clone https://github.com/amulsinfal/selenium-automation-logging-using-log4j2.git
```

2. Go to the folder selenium-automation-logging-using-log4j2 containing the testng.xml file.
```
cd selenium-automation-logging-using-log4j2
```

3. Open command prompt from this location and Run maven command in command prompt.
 ```
mvn test
```

<br><br>

<img width="1078" alt="" src="https://github.com/user-attachments/assets/1c4d7708-620d-4b2c-bbee-993b3ca318a3" />

---

### 📌 Key Takeaways:
- Configuring Log4j2 for both console and file output
- Implementing best practices for structured and meaningful log messages
- Understanding how logging enhances test debuggability, transparency, and reporting

---

### Conclusion:
Integrating Log4j2 logging has significantly improved the transparency and debugging ease of my Selenium + Java + TestNG framework. With detailed logs, I can now efficiently track each step, promptly identify issues, and maintain the framework with ease. 
