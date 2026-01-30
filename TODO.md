# 📋 Billora - Project Roadmap & Task List

## ✅ Phase 1: Core Functionality (Completed)
- [x] **Project Initialization:** Set up MERN stack architecture (Node.js, Express, React, MongoDB).
- [x] **Authentication Module:** Implement secure User Registration and Login using JWT (JSON Web Tokens).
- [x] **Subscription Management (CRUD):** Enable users to Create, Read, Update, and Delete subscription records.
- [x] **Dashboard Analytics:** Develop visual data representation using Recharts (Pie Chart & Bar Chart).
- [x] **Financial Logic:** Implement automated calculation of total monthly expenses in INR (₹).
- [x] **Status Management:** Add "Pause/Resume" functionality to exclude inactive subscriptions from cost totals.
- [x] **User Interface:** Design a responsive UI with a fully functional Dark/Light theme toggle.
- [x] **Cloud Deployment:** Deploy Backend to Render and Frontend to Vercel with continuous integration.

---

## 🚀 Phase 2: Feature Expansion (High Priority)
- [ ] **Automated Notification System:** Integrate `Nodemailer` to dispatch email alerts 3 days prior to payment due dates.
- [ ] **OAuth 2.0 Integration:** Implement "Sign in with Google" functionality using Passport.js or Firebase Auth.
- [ ] **Data Export Capability:** Develop an API endpoint allowing users to download expense reports in `.csv` or `.xlsx` format.
- [ ] **Advanced Filtering & Sorting:** Add functionality to sort subscriptions by "Cost (High-Low)" and "Renewal Date".

---

## 🛠️ Phase 3: Performance & Optimization
- [ ] **Pagination Implementation:** Limit dashboard display to 10 items per page to enhance performance for heavy users.
- [ ] **Loading State Enhancements:** Integrate skeleton loaders to improve perceived latency during data fetching.
- [ ] **Rate Limiting:** Implement backend middleware to prevent API abuse and ensure server stability.
- [ ] **Multi-Currency Support:** Architect the database to support dynamic currency conversion (USD, EUR, GBP).

---
