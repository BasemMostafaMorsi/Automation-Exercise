# 🧪Automation Exercise 

#Description

* automation exercise test * is a test automation project using Selenium and Rest Assured for wep application and Api testing . the project is designed to be modular and custmaizable , allowing easy adaptaiton to different project requist
## Repository Information 

**Owner:** [Basem Mostafa](https://github.com/BasemMostafaMorsi)

**Repository Url :**[automation exercise test](https://github.com/BasemMostafaMorsi/Automation-Exercise)

**Primary Languag :** java

## ✅Features

✔️ Framework Architecture – Developed using Java, Selenium, TestNG, and Maven, focusing on maintainability and scalability.
✔️ Design Patterns – Page Object Model (POM) and Fluent Pattern Approach for clean and scalable code.
✔️ Reusable Utilities – Smart actions for waits and element interactions for reliable and stable tests.
✔️ WebDriver Factory & Thread-Safety – For stable execution across browsers and driver management.
✔️ Comprehensive End-to-End Testing – Covers login, products, cart, checkout, and completion workflows using Data-Driven Testing (DDT) achieving high coverage.
✔️ Structured Logging – Log4j Integration for detailed logs and Custom Listeners for test monitoring.
✔️ Clear Reporting – Allure Reports providing real-time execution insights, step-level reporting, and failure analysis.

## Core Tech Stack :

💠 Java | Selenium WebDriver | TestNG | Maven
💠 Page Object Model (POM) | Fluent Pattern | Factory Pattern
💠 Data-Driven Testing | Log4j | Allure Reports | XML suite

## 🧱 Project Structure
├── src
    ├── main
    │   ├── resources
    │   │   ├── waits.properties
    │   │   ├── db.properties
    │   │   ├── seleniumGrid.properties
    │   │   ├── video.properties
    │   │   ├── META-INF
    │   │   │   └── services
    │   │   │   │   └── org.testng.ITestNGListener
    │   │   ├── allure.properties
    │   │   ├── environment.properties
    │   │   ├── extensions
    │   │   │   └── HaramBlur.crx
    │   │   ├── webapp.properties
    │   │   └── log4j2.properties
    │   └── java
    │   │   └── com
    │   │       └── automationexercices
    │   │           ├── drivers
    │   │               ├── WebDriverProvider.java
    │   │               ├── UITest.java
    │   │               ├── AbstractDriver.java
    │   │               ├── Browser.java
    │   │               ├── SafariFactory.java
    │   │               ├── GUIDriver.java
    │   │               ├── FirefoxFactory.java
    │   │               ├── EdgeFactory.java
    │   │               └── ChromeFactory.java
    │   │           ├── pages
    │   │               ├── LogoutPage.java
    │   │               ├── ContactUsPage.java
    │   │               ├── TestCasesPage.java
    │   │               ├── DeleteAccountPage.java
    │   │               ├── PaymentPage.java
    │   │               ├── ProductDetailsPage.java
    │   │               ├── CartPage.java
    │   │               ├── SignupLoginPage.java
    │   │               ├── components
    │   │               │   └── NavigationBarComponent.java
    │   │               ├── SignupPage.java
    │   │               ├── ProductsPage.java
    │   │               └── CheckoutPage.java
    │   │           ├── utils
    │   │               ├── TimeManager.java
    │   │               ├── OSUtils.java
    │   │               ├── TerminalUtils.java
    │   │               ├── dataReader
    │   │               │   ├── ExcelReader.java
    │   │               │   ├── JsonReader.java
    │   │               │   └── PropertyReader.java
    │   │               ├── logs
    │   │               │   └── LogsManager.java
    │   │               ├── report
    │   │               │   ├── AllureEnvironmentManager.java
    │   │               │   ├── AllureConstants.java
    │   │               │   ├── AllureAttachmentManager.java
    │   │               │   ├── AllureReportGenerator.java
    │   │               │   └── AllureBinaryManager.java
    │   │               ├── WaitManager.java
    │   │               └── actions
    │   │               │   ├── BrowserActions.java
    │   │               │   ├── FrameActions.java
    │   │               │   ├── AlertActions.java
    │   │               │   └── ElementActions.java
    │   │           ├── validations
    │   │               ├── Verification.java
    │   │               ├── Validation.java
    │   │               └── BaseAssertion.java
    │   │           ├── apis
    │   │               ├── Builder.java
    │   │               └── UserManagementAPI.java
    │   │           ├── media
    │   │               ├── ScreenshotsManager.java
    │   │               └── ScreenRecordManager.java
    │   │           ├── FileUtils.java
    │   │           └── listeners
    │   │               └── TestNGListeners.java
    └── test
    │   ├── resources
    │       └── test-data
    │       │   ├── cart-data.json
    │       │   ├── login-data.json
    │       │   ├── product-details-data.json
    │       │   ├── products-data.json
    │       │   ├── register-data.json
    │       │   └── checkout-data.json
    │   └── java
    │       └── com
    │           └── automationexercices
    │               └── tests
    │                   ├── BaseTest.java
    │                   ├── api
    │                       └── RegisterTestAPI.java
    │                   └── ui
    │                       ├── CartTest.java
    │                       ├── ProductDetailsTest.java
    │                       ├── ProductsTest.java
    │                       ├── LoginTest.java
    │                       ├── RegisterTest.java
    │                       ├── CheckoutTest.java
    │                       ├── PaymentTest.java
    │                       └── InvoiceTest.java
├── testng.xml
├── .github
    ├── dependabot.yml
    └── workflows
    │   └── E2E Regression Pipeline.yml
├── .gitignore
└── pom.xml
## Run the tests
mvn test 
## 👨‍💻 Author
**Basem Mostafa**

**junior Automation Engineer**

[Gmail ](basem.mostafa.morsy@gmail.com)
