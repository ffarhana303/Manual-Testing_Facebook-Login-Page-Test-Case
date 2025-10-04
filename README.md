<!-- FACEBOOK LOGIN TESTING README -->
<h1 align="center">🔐 Facebook Login Page — Manual Testing Project</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Testing-Type-Manual-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Platform-Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-✅%20Completed-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/QA%20Engineer-Farhana%20Islam-ff69b4?style=flat-square" />
</p>

---

## 🧭 **Project Overview**

This project documents **manual test cases** designed for the **Facebook Login Page** — ensuring that all authentication and UI elements function as expected.  
Each test case is based on **SRS requirements** and focuses on **functionality**, **security**, and **usability**.

> 💡 Goal: Verify Facebook’s login process for both valid and invalid user behaviors, ensuring smooth authentication and strong security.

---

## 🧩 **Module Details**

| 🧱 Module | 📝 Description |
|:-----------|:----------------|
| 👤 **User Authentication** | Verify successful login using valid credentials. |
| 🚫 **Invalid Login Handling** | Ensure proper error messages for wrong credentials. |
| 🧠 **Field Validation** | Check empty, invalid, or special character inputs. |
| 🔐 **Password Security** | Confirm masking and toggle visibility features. |
| 📱 **Responsive UI** | Test layout across devices (desktop, mobile). |
| 🕒 **Session Handling** | Validate “Remember Me” persistence. |
| 🔒 **Forgot Password Flow** | Verify password recovery and email link functionality. |
| 🌐 **Third-Party Login (if available)** | Validate login via Google/Apple. |

---

## 📂 **Included File**

| 📄 File Name | 📘 Description |
|---------------|----------------|
| `Facebook login page test cases.xlsx` | Contains detailed manual test cases for Facebook Login features. |

---

## 🧾 **Sample Test Case**

| Field | Details |
|--------|----------|
| 🆔 **Test ID** | TC_FB_001 |
| 🧩 **Module** | Login |
| 🎯 **Scenario** | Verify login with valid email and password |
| ⚙️ **Precondition** | User account must exist |
| 🪜 **Test Steps** | 1️⃣ Open Facebook login page<br>2️⃣ Enter valid credentials<br>3️⃣ Click “Log In” |
| ✅ **Expected Result** | User logs in successfully and navigates to News Feed |
| 🧪 **Actual Result** | Login successful |
| 🟢 **Status** | Pass |

---

## 📊 **Test Summary**

| Metric | Description | Example |
|:--------|:--------------|:----------|
| 🔢 **Total Test Cases** | Designed test scenarios | 60 |
| 🟢 **Passed** | Successfully executed | 55 |
| 🔴 **Failed** | Found defects or mismatches | 3 |
| 🟡 **Blocked/Pending** | Not executed due to dependency | 2 |
| 📈 **Pass Rate** | `(Passed / Total) × 100` | 91.6% |

---

## 🧪 **Testing Approach**

### 1️⃣ **Test Design**
- Based on **SRS requirements & user journey**.  
- Includes **positive**, **negative**, and **boundary** scenarios.

### 2️⃣ **Test Execution**
- 🧭 **Environment:** Web Browser (UI Testing)  
- 💻 **Platforms:** Windows 10, Android 13  
- 🌐 **Browsers Tested:** Chrome, Firefox, Edge  

### 3️⃣ **Defect Tracking**
- 🪲 Issues logged in **Excel/JIRA** with:  
  - Steps to Reproduce  
  - Expected vs Actual  
  - Severity (Critical, Major, Minor)  
  - Screenshot Evidence  

---

## 💡 **Key Test Scenarios**

| 🆔 | 🎯 Scenario | 💬 Expected Result | 🧩 Status |
|:---|:-------------|:------------------|:-----------|
| TC_FB_001 | Login with valid credentials | User logs in successfully | ✅ Pass |
| TC_FB_002 | Invalid password entry | “Incorrect password” message displayed | ✅ Pass |
| TC_FB_003 | Empty email field | “Email required” alert displayed | ✅ Pass |
| TC_FB_004 | Empty password field | “Password required” alert displayed | ✅ Pass |
| TC_FB_005 | Forgot Password link | Redirects to recovery page | ✅ Pass |
| TC_FB_006 | Invalid email format | “Invalid email” validation error | ✅ Pass |
| TC_FB_007 | Password visibility toggle | Password shown when toggled | ✅ Pass |
| TC_FB_008 | Deactivated account login | Error message displayed | 🔴 Fail |
| TC_FB_009 | “Remember Me” feature | User stays logged in after reload | ✅ Pass |
| TC_FB_010 | Mobile responsiveness | Layout adjusts properly | ✅ Pass |

---

## 🧭 **Execution Steps**

1. 📥 **Download** → `Facebook login page test cases.xlsx`  
2. 📑 **Review** → Each test case and test data  
3. 🧪 **Execute** → Perform steps on Facebook Login UI  
4. 🐞 **Log Defects** → If Expected ≠ Actual  
5. 📊 **Update Results** → Pass / Fail / Blocked  

---

## 🧱 **QA Best Practices**

✅ Cover **positive & negative** test paths.  
✅ Include **test data examples** for clarity.  
✅ Execute across **multiple browsers & devices**.  
✅ Log **screenshots & evidence** for all defects.  
✅ Maintain **clear and consistent test IDs**.  

---

## 🚀 **Future Enhancements**

- 🤖 Automate login test flow using **Selenium + JavaScript**.  
- 📈 Integrate with **TestRail / Zephyr** for reporting.  
- ☁️ Add API-level test coverage for login endpoints.  
- 💾 Generate HTML reports from Excel execution results.  

---

## 👩‍💻 **Project Contributors**

| 🧠 Role | 👤 Name |
|----------|-----------|
| 🧪 **QA Lead** | Farhana Islam |
| 💼 **Test Engineer** | [Farhana] |
| 🗓️ **Last Updated** | October 2025 |
| 🧾 **Version** | v1.0 |

---

## 🌟 **Project Tagline**

> 🔐 *"Every secure login starts with precise testing."*

---

<p align="center">
  <img src="https://img.shields.io/badge/Manual_Testing-Completed-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Facebook_Login_Module-Tested-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
  <img src="https://img.shields.io/badge/SRS_Based_Testing-✓-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/QA_Excellence-Farhana_Islam-ff69b4?style=for-the-badge" />
</p>
