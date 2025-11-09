# 🛒 Demo Web Shop - Manual & Automation Testing Project

![Testing Badge](https://img.shields.io/badge/Testing-DemoWebShop-blue)
![Selenium Badge](https://img.shields.io/badge/Selenium-Java-brightgreen)
![TestNG Badge](https://img.shields.io/badge/TestNG-Framework-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-Free-lightgrey)

---

## 📘 Project Overview

This repository contains **end-to-end testing (Manual + Automation)** of the [Demo Web Shop](https://demowebshop.tricentis.com/) website — an e-commerce web application.

The goal of this project is to ensure the **functionality, reliability, and performance** of the website through structured manual testing and automated test execution using **Selenium with Java and TestNG** following the **Page Object Model (POM)** design pattern.

---

## 🧾 Project Highlights

### ✅ Manual Testing
- Created a **detailed Test Plan** covering objectives, scope, testing types, tools, and deliverables.
- Designed **Test Scenarios & Test Cases** with clear steps, expected and actual results.
- Created a **Mind Map** for test coverage visualization.
- Logged **Bug Reports** with severity, priority, and reproducible steps.
- Prepared a **Test Summary Report** after execution.
- Ensured complete coverage of key features like:
  - User Registration & Login  
  - Product Search  
  - Add to Cart & Checkout  
  - Payment Process  
  - Order History & Logout  

📁 **Manual Testing Documents**

📂 Manual_Testing/
┣ 📄 Test_Plan.docx
┣ 📄 Test_Scenarios_and_Test_Cases.xlsx
┣ 📄 Bug_Report.xlsx
┣ 📄 Mind_Map.png
┣ 📄 Test_Summary_Report.docx


---

### 🤖 Automation Testing

Automated the critical end-to-end user flows using **Selenium WebDriver, Java, and TestNG** following the **Page Object Model (POM)** structure for reusability and maintainability.

📁 **Automation Framework Structure**

📂 DemoWebShop_Automation/
┣ 📂 src/main/java/
┃ ┣ 📂 pages/ # Page Object files (LoginPage, RegisterPage, CartPage, etc.)
┃ ┣ 📂 utils/ # Common utilities (Driver setup, ConfigReader, etc.)
┣ 📂 src/test/java/
┃ ┣ 📂 testcases/ # Test classes using TestNG annotations
┣ 📂 test-output/ # TestNG HTML reports
┣ 📄 testng.xml # Test suite configuration
┣ 📄 pom.xml # Maven dependencies
┣ 📄 README.md


🧩 **Key Features of Automation Framework**
- Implemented **Page Object Model (POM)** for modular design.
- Used **TestNG** for test grouping, prioritization, and parallel execution.
- Integrated **Assertions** for validation of functional behavior.
- Added **Implicit & Explicit Waits** for synchronization.
- Generated **Extent Reports** for rich HTML reporting (optional).
- Designed reusable methods for login, search, and checkout flows.

🧠 **Automated Scenarios Include**
- User registration and login
- Searching and adding items to cart
- Verifying cart and product details
- Performing checkout
- Validating success messages
- Logging out successfully

---

## 🧪 Tools & Technologies Used

| Category | Tools / Technologies |
|-----------|----------------------|
| **Automation Tool** | Selenium WebDriver |
| **Programming Language** | Java |
| **Testing Framework** | TestNG |
| **Design Pattern** | Page Object Model (POM) |
| **Build Tool** | Maven |
| **IDE Used** | IntelliJ IDEA / Eclipse |
| **Manual Testing Docs** | MS Word, Excel, XMind |
| **Reporting Tool** | Extent Reports / TestNG Reports |

---

## 🚀 How to Run Automation Tests

### 🔧 Prerequisites
- Install **Java JDK (8 or above)**
- Install **Maven**
- Install **IntelliJ IDEA / Eclipse**
- Clone this repository:
  ```bash
  git clone https://github.com/Shivshanker869/DemoWebShop.git
```
