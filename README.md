# 🏨 Booking.com UI Automation - Alexis Roman

This project showcases automated UI tests for [Booking.com](https://www.booking.com) using **Playwright + TypeScript**.  
It focuses on testing the hotel search functionality, result filtering, and interaction flow — all without logging in.

---

## 📌 Stack

- ✅ Playwright
- ✅ TypeScript
- ✅ JSON for Data-Driven Testing (DDT)
- ✅ GitHub Actions (coming soon)
- ✅ Screenshots for visual evidence

---

## 🎯 Features Automated

| Test Case | Description |
|-----------|-------------|
| 🔍 Search Hotel | Enters destination and dates, then triggers search |
| 🗂️ Apply Filters | Applies star rating and price filters |
| 📋 Verify Result List | Validates the visibility of results after filtering |
| 📑 View Hotel Detail | Opens first result and checks for key hotel info |

---

## 🧪 Test Structure

- `/tests` → All `.spec.ts` files by module
- `/data` → Dynamic inputs (JSON)
- `/evidence` → Screenshot capture per test step
- `playwright.config.ts` → Custom config and setup

---

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Run tests
npx playwright test

# Open test report
npx playwright show-report
