# QA Automation & Python Practice Portfolio

Welcome to my QA Automation and Python practice repository. This portfolio contains end-to-end automated testing frameworks, API test suites, data processing scripts, and core Python exercises developed during my QA Automation training.

---

## 🛠 Tech Stack & Tools

* **Languages:** Python
* **Test Automation & Frameworks:** Selenium WebDriver, PyTest, Page Object Model (POM)
* **API Testing:** Requests, Postman
* **Data Handling & Analysis:** Pandas, OpenPyXL, File I/O
* **Utilities & Practice:** Built-in Python Libraries (`logging`, `os`, `shutil`, `pathlib`)

---

## 📁 Portfolio Projects Overview

### 1. Automation Suites & Projects

* **[letskodeit-ui-automation](./letskodeit-ui-automation)**
  * **Tech Stack:** Python, Selenium WebDriver, PyTest, Page Object Model (POM)
  * **Description:** End-to-end Web UI test automation framework. Demonstrates dynamic element interactions, JavaScript Alerts, iframe context switching, hover actions (`ActionChains`), multi-tab handling, and explicit synchronization (`WebDriverWait`).

* **[user-balance-api-automation](./user-balance-api-automation)**
  * **Tech Stack:** Python, Requests, PyTest
  * **Description:** Automated E2E API test suite. Covers non-admin user registration, authentication header/token management, state updates (account balance top-up), and response payload data assertions (`final_balance == default_balance + added_amount`).

* **[exam-results-analyzer](./exam-results-analyzer)**
  * **Tech Stack:** Python, Pandas, OpenPyXL, Logging
  * **Description:** Automated data processing pipeline for university examination results. Handles Excel report generation, score analysis (max/min/student count), structured logging (`app.log`), and dynamic directory lifecycle management (`os`, `shutil`).

---

### 2. Python Core & Practice Utilities

* **[oop-principles](./oop-principles)**
  * **Description:** Practical implementation of Object-Oriented Programming principles (Abstraction, Encapsulation, Inheritance, Polymorphism) in Python.

* **[working-with-files](./working-with-files)**
  * **Description:** Helper functions and scripts for Python File I/O operations, text data parsing, dynamic log extraction, and path management using `os` and `pathlib`.

* **[advanced-ui-automation-practice](./advanced-ui-automation-practice)** 
  * **Tech Stack:** Python, Selenium WebDriver, Dynamic Waits (`WebDriverWait`), File I/O
  * **Description:** Automation scripts covering complex UI interaction patterns across multiple testing environments (`uitestingplayground.com` and `letskodeit.com`):
    * **Dynamic Element Verification:** Validating hidden elements, dynamic button text changes, and progress bar completion duration tracking.
    * **User Interactions & Synchronization:** ActionChains (`Mouse Hover`), explicit synchronization (`WebDriverWait`), multi-tab handling, and JavaScript alerts.
    * **Automation Data Logging:** Extracting runtime dynamic attributes, alert messages, and validation errors directly into local `.txt` reports (`live_coding_text.txt`).
---

## 🚀 How to Run locally

1. **Clone the repository:**
   ```Bash
   git clone https://github.com/MaryOnanyan/qa-projects.git
   cd qa-projects

    ```Bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows: .venv\Scripts\activate
    Install dependencies:

    ```Bash
    pip install -r requirements.txt
    Run all tests:

    ```Bash
    pytest
