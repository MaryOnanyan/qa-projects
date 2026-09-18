# qa-projects
Automated test suites and QA framework practices using Python, PyTest, Selenium, and Requests.

## 1. Web UI Automation Practice – LetsKodeIt

### Overview
Automated end-to-end UI testing scenario for the LetsKodeIt Practice platform utilizing Python, Selenium WebDriver, and PyTest. Implemented using the **Page Object Model (POM)** design pattern for scalability and maintainability.

### Key Scenarios & Features Covered
* **Dynamic Web Elements & Alerts:** Handling JavaScript Alert popups and extracting dynamic text.
* **File I/O Operations:** Dynamically logging runtime extracted text, element attributes, and error validation messages into external `.txt` files.
* **Element Manipulation:** Hiding/showing DOM elements and extracting element attribute values.
* **Advanced Mouse Interactions:** Mouse hover actions (`ActionChains`) to navigate menus.
* **Multi-Tab & Window Management:** Handling browser tab switching and navigation.
* **Form Validation:** Negative test scenario for user authentication (Sign In) and capturing error messages.
* **Synchronization:** Explicit Waits (`WebDriverWait`) applied across interactions for test stability.

### Tech Stack & Tools
* **Language:** Python
* **Framework:** PyTest
* **Automation Tool:** Selenium WebDriver
* **Design Pattern:** Page Object Model (POM)
