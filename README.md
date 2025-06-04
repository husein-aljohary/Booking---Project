# 🏨 Booking.com - Manual QA Test Report

This project presents a comprehensive **Manual QA Test Report (STR)** for **Booking.com**, one of the world’s largest digital travel platforms. The goal is to ensure quality assurance through detailed testing of all core functionalities and user flows.

## 🔍 Overview

- **Project Name:** Booking.com Web QA
- **Testing Type:** Manual Testing
- **Platform:** Web (Desktop)
- **Reported By:** Husein Aljohary
- **Date:** April 2025
- **Website:** [https://www.booking.com](https://www.booking.com)

## 🎯 Objectives

- Validate booking, filtering, login, and payment flows.
- Detect bugs affecting user experience and conversion.
- Ensure cross-browser compatibility and responsiveness.
- Confirm accurate error messages and proper form validation.
- Identify accessibility and UI/UX improvement areas.

## 🧪 Scope of Testing

✔️ Search Functionality  
✔️ Registration & Login (OTP flow)  
✔️ Hotel Booking Process  
✔️ Payment & Confirmation  
✔️ Filtering & Sorting  
✔️ Notifications & User Profile  
✔️ Account Settings  
✔️ UI/UX Elements  
✔️ Footer & Legal Links  
✔️ Accessibility & Language Support

## 🧰 Tools Used

| Tool     | Purpose                     |
|----------|-----------------------------|
| **TestRail** | Test Case Management        |
| **Jira**     | Bug Tracking & Reporting    |

## 📈 Metrics

- ✅ **Test Cases Executed:** Covered major flows
- 🐞 **Total Bugs Reported:** 30
  - High Priority: 14
  - Medium Priority: 10
  - Low Priority: 6

## 🐞 Example Bugs (from Jira)

| Bug ID   | Summary                                                    | Priority |
|----------|------------------------------------------------------------|----------|
| BOOK-1   | Search without selecting dates returns hotel list          | Low      |
| BOOK-4   | Accepts invalid email domains                              | Medium   |
| BOOK-18  | Name field accepts invalid characters                      | High     |
| BOOK-24  | COVID-19 FAQs page not found                              | Highest  |
| BOOK-28  | No accessibility support                                    | High     |

➡️ See full list in `STR Booking.pdf` or on [Jira](https://husein390.atlassian.net/browse/BOOK-1)

## ✅ Exit Criteria

- All core flows tested.
- High/critical bugs logged and highlighted.
- No blockers remain in login, booking, or payment.
- Regression testing performed after bug fixes.

## 📌 Recommendations

- Add stronger form validations (email, phone, names).
- Fix broken links in footer and support sections.
- Improve accessibility and responsiveness.
- Add clear "Remove Filters" and error prompts.
- Ensure data persistence across language switches.
- Strengthen OTP and payment validation logic.

## 📄 Files

- [`STR Booking.pdf`](./STR%20Booking.pdf): Full test plan, bugs, and cases report.

## 🌐 Links

- 🔗 [Booking.com](https://www.booking.com)
- 🐞 [Jira Bug Tracker](https://husein390.atlassian.net/browse/BOOK-1)

---

> This project reflects a detailed QA workflow, real-world bug tracking, and structured documentation. A strong example of manual testing for high-scale web platforms.
