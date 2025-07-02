 Cross-Browser Testing – Test Report

 Website: https://www.saucedemo.com/

---

 Login Credentials:
- *Username*: standard_user
- *Password*: secret_sauce

---

 Test Summary:

| Test Case ID | Browser | Device | Description               | Expected Result        | Actual Result          | Status |
|--------------|---------|--------|---------------------------|------------------------|------------------------|--------|
| TC_01        | Chrome  | Android | Login with valid user     | Login successful       | Login successful       | ✅ Pass |
| TC_02        | Brave   | Android | Login with valid user     | Login successful       | Login successful       | ✅ Pass |
| TC_03        | Chrome  | Android | Check UI layout after login | All elements visible | All elements fine     | ✅ Pass |
| TC_04        | Brave   | Android | Responsive design check   | Proper layout          | Responsive layout ok   | ✅ Pass |

---

 Browsers Not Tested:
- Firefox, Safari, and Edge due to no desktop access and BrowserStack session limits.

---
 Final Notes:
- Website works well on mobile browsers (Chrome, Brave)
- Login and UI are stable
- More browser/device testing recommended if resources available
