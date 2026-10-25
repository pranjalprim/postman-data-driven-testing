# 🚀 Data-Driven API Automation Testing with Postman & Newman

This repository contains an automated API testing framework for the **Restful Booker API** (`https://restful-booker.herokuapp.com/booking/`). 

The primary objective of this project is to demonstrate **Data-Driven Testing (DDT)** using dynamic datasets (CSV/JSON), Postman collection runner, and automated execution via **Newman CLI**.

---

## 📌 Project Features & Highlights
- **Data-Driven Testing (DDT):** Test scripts dynamically execute against multiple data rows from an external CSV file (`Dataset_For_DDT.csv`).
- **End-to-End Automation:** Command-line test execution powered by **Newman**.
- **Automated Reporting:** Generates detailed execution summary reports (CLI & HTML).
- **Assertions:** Validates HTTP status codes, response times, headers, and JSON body structures across iterations.

---

## 📁 Repository Structure

```text
Booking/
├── DDT_COLLECTION.postman_collection.json   # Postman API Test Collection
├── DDT_ENVIRONMENT.postman_environment.json  # Environment Variables
├── Dataset_For_DDT.csv                       # CSV Test Dataset (6 Iterations)
├── newman/                                    # Generated HTML & CLI Execution Reports
└── README.md                                 # Project Documentation
