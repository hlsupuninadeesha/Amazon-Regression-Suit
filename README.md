#Read before running the suit

##Selenium Automation Framework for Amazon

## **Features**
- Built using **Java** and **TestNG**.
- Utilizes the **Page Object Model (POM)** for better test maintenance.
- Implements a **data-driven approach** to fetch test data dynamically from Excel files.
- Generating detailed test reports using **Allure Reporting** will be implemented in upcoming versions.
- Cross-browser testing support using **WebDriverManager**.

## **Pre-Requisites**
1. Install **Java JDK** (1.8 or above).
2. Install **Maven** for dependency management.
3. Install a browser (e.g., Google Chrome).
4. Clone this repository to your local machine.

## **How to Run the Tests**
1. **Configure the Test Data:**
-Username and passwords in given excel are dummy data.Change them with real values before running.

2.**Install Maven Dependencies:**
   Run the following command in the project directory:
   bash command
   mvn clean install
   
3.**Run the Tests**
-Command prompt >> go to project 
-run command mvn test
