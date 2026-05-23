# QA Automation Assignment using Playwright 🚀

## 📌 Project Overview

This project demonstrates an end-to-end QA Automation Framework using Playwright with JavaScript.  
It includes both:

- UI Automation Testing using DemoQA Book Store
- API Automation Testing using ReqRes API

The framework follows:

- Page Object Model (POM)
- Data-Driven Testing
- Reusable API Framework Design

---

# 🛠️ Tech Stack

- Playwright (JavaScript)
- Node.js
- Page Object Model (POM)
- JSON for Test Data Management
- Environment Variables (.env)

---

# 📂 Project Structure

```bash
qa-automation-playwright/
│
├── tests/
│   ├── user.spec.js
│   └── demoqa.spec.js
│
├── API/
│   ├── apiBase.js
│   └── userApi.js
│
├── POM/
│   ├── base.js
│   ├── book.js
│   └── login_page.js
│
├── test_data/
│   └── data.json
│
├── .env
├── playwright.config.js
├── package.json
└── README.md
```

---

# ✅ Features Implemented

## 🔹 UI Automation (DemoQA)

- Navigate to Book Store Application
- Login with valid credentials
- Validate username
- Validate logout button
- Search for a book
- Validate search results
- Extract and store book details
- Logout functionality

---

## 🔹 API Automation (ReqRes)

- Create User (POST)
- Validate response status code
- Fetch and validate user details (GET)
- Update user details (PUT)
- Response validation
- API chaining where applicable

---

# 📁 Test Data Management

All test data is maintained in:

```bash
test_data/data.json
```

Environment variables are stored in:

```bash
.env
```

---

# ▶️ How to Run the Project

## Install Dependencies

```bash
npm install
```

## Run All Tests

```bash
npx playwright test
```

## Run Specific Test File

```bash
npx playwright test tests/user.spec.js
```

---

# 📊 Playwright HTML Report

Generate and open the Playwright HTML Report using:

```bash
npx playwright show-report
```

---

# 💡 Framework Design Approach

- Implemented Page Object Model (POM) for maintainability
- Used Data-Driven Testing with JSON
- Separated UI and API layers
- Added reusable API methods
- Used environment variables for configuration
- Created scalable and reusable framework structure

---

# 🚀 Conclusion

This project demonstrates a scalable and maintainable QA Automation Framework using Playwright with JavaScript.

The framework combines both:

- UI Automation
- API Automation

while following industry-standard automation practices and framework design principles.
