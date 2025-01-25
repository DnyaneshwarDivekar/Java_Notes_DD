# Java_Notes_DD
Java Notes By DD

# Automation Testing and SDLC Notes

## 1) What is Automation Testing? Why?

### Manual Testing
- Test cases are executed by human testers.
- Time-consuming, prone to human error.

### Automation Testing
- Uses scripts and tools to automatically execute test cases.
- Increases testing efficiency, speed, and repeatability.
- Reduces human errors and provides consistent results.

---

## 2) Software Development Life Cycle (SDLC)

### 1. Requirement Gathering/Collection
- **Sources**: 
  - **Business Analyst (BA)** or **Product Owner (PO)**
  - **Documents**: FRD (Functional Requirements Document), BRD (Business Requirements Document), URD (User Requirements Document)
  
#### Types of Companies:
- **Service-Based Companies** (e.g., TCS, Wipro, Infosys):
  - Focus: Tech Support, BPO, Development Support, Client Projects.
  - Example: **ABC Bank** for a Loan Calculator App.

- **Product-Based Companies** (e.g., Zoom, Google, Amazon):
  - Focus: Market Study, Broad User Base.
  - Example: **Google Products** like Gmail, YouTube, G-Maps.

---

### 2. Requirement Analysis
- **Client’s Input**: Defines specifics like loan amount, tenure, interest rate, and EMI.
- **Documents**: **Software Requirement Document (SRD)** / **Software Requirement Specification (SRS)**.

---

### 3. Design Phase
- **High-Level Design (HLD)**:
  - Focus on system architecture.
  - Involves System Architect and Design Experts.
  
- **Low-Level Design (LLD)**:
  - Detailed design for individual components.
  - UI/UX experts are involved in user interface design.

---

### 4. Development Phase
- **Frontend Development**:
  - Technologies: JavaScript, HTML, CSS.
  - Frameworks: Angular, Vue.js, MEAN, MERN stacks.
  
- **Backend Development**:
  - Languages: Java, Python, C, C++.
  - Focus on backend API logic.

- **Database Development**:
  - Types: SQL (e.g., MySQL), No-SQL (e.g., MongoDB).
  
- **Full Stack Development**:
  - Involves both frontend and backend technologies.

---

### 5. Testing Phase
- **Software Testing Life Cycle (STLC)**:
  1. **Requirement Study**: Understanding user stories using tools like Jira or Azure Board.
  2. **Test Case Design**: Developing test cases based on requirements.
  3. **Test Execution**: Executing tests on different builds (e.g., 1.0, 1.1, 2.0, etc.).
  4. **Bug Reporting**: Creating and tracking bugs/issues.
     - Bug Lifecycle: New → In Progress → Fixed → Closed.
  5. **Sign-Off**: QA reporting and final approval.

---

### 6. Deployment Phase
- **Production and Maintenance**:
  - Code deployment into live environments (QA, UAT, Production).
  - Ongoing support and bug fixes after deployment.

---

## 3) Automation Testing Phase
- **Manual Testing Cycle**:
  - Test cases are executed manually during early stages of the project.
  
- **Automation Testing Cycle**:
  - Test cases are automated after manual testing to increase efficiency.
  - Automation applies to web, Android, and iOS apps.

#### Test Types:
- **UI Testing**: Ensures the user interface works as expected.
- **API Testing**: Verifies API functionality and integration.
- **Unit Testing**: Verifies individual components or units of the software.

---

### 4) Automated Test Example: Loan Calculator App
- **Objective**: Automate test cases for a loan calculator app.
  - Test Steps:
    1. Open the URL.
    2. Enter loan amount, tenure, interest rate.
    3. Click "Calculate EMI" button.
    4. Expected Result: Monthly EMI schedule is displayed.
    5. **Pass/Fail**: Match the expected result with the actual outcome.

---

## 4) Programming Language & Tools for Automation
- **Core Programming Language**: Java (Core and Advanced Java).
  - **Core Java**: SE (Standard Edition).
  - **Advanced Java**: EE (Enterprise Edition).

- **Testing Frameworks**:
  - **Selenium** for UI automation.
  - **TestNG** for managing test cases and generating reports.

---

### 5) Core Java Concepts

#### 1. Java Environment Components:
  - **JDK (Java Development Kit)**: Includes JVM, JRE, and libraries.
  - **JRE (Java Runtime Environment)**: Includes JVM and API libraries.
  - **JVM (Java Virtual Machine)**: Executes bytecode and handles memory management.

#### 2. Access Modifiers:
  - **Public**: Accessible by any class or package.
  - **Private**: Accessible only within the same class.
  - **Protected**: Accessible within the same package and subclasses.
  - **Default**: Accessible within the same package (no modifier).
  - **Access Modifier Hierarchy**: `private < default < protected < public`

#### 3. Object-Oriented Programming (OOP) Principles:
  1. **Inheritance**: Child classes inherit properties and methods of parent classes.
  2. **Abstraction**: Hides complex implementation details and shows only the necessary functionality.
  3. **Polymorphism**: Ability to use a method in multiple ways (e.g., method overloading and overriding).
  4. **Encapsulation**: Bundling of data and methods to operate on that data within one unit (class).

#### 4. Constructors:
  - **Non-Parameterized Constructor (Default Constructor)**: Constructor without parameters.
  - **Parameterized Constructor**: Constructor with parameters to initialize objects with specific values.

#### 5. Types of Variables:
  - **Static Variable**: Shared by all instances of a class.
  - **Non-static (Instance) Variable**: Belongs to individual objects.
  - **Local Variable**: Defined within methods or code blocks.

---

### 6) Code Debugging Techniques
- **Breakpoints**: Halting the execution of a program at specific points to inspect values.
- **Step Over**: Executes the current line of code but does not step into method calls.
- **Step Into**: Enters the method being called to see the execution flow within.
- **Error Types**:
  - **Syntax Errors**: Errors detected during compilation (e.g., missing semicolons).
  - **Logical Errors**: Errors that occur during execution but do not prevent the program from running.

---

### Additional Notes on Testing and Automation
- **CI/CD Pipelines**:
  - Continuous Integration and Continuous Deployment for automating the testing and deployment process.
- **Build Versions**:
  - Incremental build versions (e.g., 1.0, 1.1, 2.0, 2.1) to track releases for web, Android, and iOS platforms.


