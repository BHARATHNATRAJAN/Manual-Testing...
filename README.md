# Manual Testing

This repository contains my **Manual Testing practice, test cases, test scenarios, bug reports, and testing documentation**.

## 📌 About the Project

The purpose of this repository is to practice software testing concepts using real-world applications and examples.

I have created and documented different testing activities such as:

* Test Scenarios
* Test Cases
* Test Data
* Equivalence Partitioning
* Boundary Value Analysis
* Bug Reports
* Test Plans
* Functional Testing
* Regression Testing
* Smoke Testing
* Sanity Testing
* Positive & Negative Testing

## 🛠️ Application Tested

### Amazon

Amazon is used as a real-world application for practicing manual testing.

Testing areas include:

* Login
* Product Search
* Product Details
* Add to Cart
* Cart Quantity
* Price Validation
* Checkout
* Order-related functionality

## 📂 Repository Structure

```text
Manual-Testing/
│
├── Test-Plan/
│   └── Amazon-Test-Plan.xlsx
│
├── Test-Cases/
│   └── Amazon-Test-Cases.xlsx
│
├── Bug-Reports/
│   └── Bug-Reports.xlsx
│
├── Test-Scenarios/
│   └── Test-Scenarios.xlsx
│
├── Boundary-Value-Analysis/
│
├── Equivalence-Partitioning/
│
└── README.md
```

## 🧪 Testing Techniques

### 1. Equivalence Partitioning

The input data is divided into valid and invalid groups called equivalence classes.

**Example:**

Requirement: Customer can book 1–6 tickets.

* Valid: 1–6
* Invalid: 0 or less
* Invalid: 7 or more

### 2. Boundary Value Analysis

Testing is performed around the boundaries of valid input ranges.

**Example:**

For 1–6 tickets:

* 0 → Invalid
* 1 → Valid
* 2 → Valid
* 5 → Valid
* 6 → Valid
* 7 → Invalid

## 🐞 Bug Reporting

Bugs are documented with:

* Bug ID
* Title
* Description
* Steps to Reproduce
* Expected Result
* Actual Result
* Severity
* Priority
* Status
* Evidence/Screenshot

## 📊 Test Case Format

| Field           | Description                   |
| --------------- | ----------------------------- |
| Test Case ID    | Unique test case number       |
| Test Scenario   | Functionality being tested    |
| Test Steps      | Steps to perform the test     |
| Test Data       | Input data                    |
| Expected Result | Expected application behavior |
| Actual Result   | Actual application behavior   |
| Status          | Pass/Fail                     |

## 🎯 Objective

The main objective of this repository is to build practical knowledge in **Software Testing and Quality Assurance** and maintain testing artifacts that can be used for learning and portfolio purposes.

## 👨‍💻 Skills

* Manual Testing
* Test Case Design
* Test Scenario Design
* Functional Testing
* Regression Testing
* Smoke Testing
* Sanity Testing
* Equivalence Partitioning
* Boundary Value Analysis
* Bug Reporting
* Test Documentation
* Git & GitHub

## 🚀 Future Learning

I am also planning to learn:

* Automation Testing
* Python for Testing
* Selenium
* API Testing
* SQL
* Postman
* PyTest

## 📌 Note

This repository is created for **learning and testing practice purposes**. The test cases and results are based on the application's behavior observed during testing.
