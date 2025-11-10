Selenium 4 Java Utility Library

A modular, ready-to-use Selenium 4 test automation framework built using Java + TestNG + WebDriverManager.
This library includes all the most commonly used utilities and design patterns to help you start automation faster and follow best practices.

🧩 Features

🔧 Driver Management via WebDriverManager (no manual setup)

⚙️ ConfigReader for flexible environment handling

⏳ WaitUtils for smart explicit and fluent waits

🧠 ElementActions for reliable element interactions

🧾 JSUtils for JavaScript-based actions

📸 ScreenshotUtil to capture test evidence automatically

🧱 BaseTest / BasePage structure following Page Object Model (POM)

🧪 Sample Test & Page for quick start

🧰 Compatible with Maven + TestNG

📦 Quick Start
# Clone the repo
git clone https://github.com/<your-username>/selenium4-lib.git
cd selenium4-lib

# Run tests
mvn clean test

📚 Folder Structure
src/
 ├─ main/java/com/example/
 │   ├─ driver/           → WebDriver factory
 │   ├─ pages/            → Base and sample page classes
 │   └─ utils/            → Common utilities (waits, config, screenshots)
 ├─ test/java/com/example/tests/ → TestNG tests
 └─ test/resources/       → config.properties
