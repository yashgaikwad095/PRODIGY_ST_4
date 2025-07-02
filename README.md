# PRODIGY_ST_4
# Task 04 – Cross-Browser Testing with BrowserStack

 Objective:
To test the login functionality and UI consistency of the demo site [SauceDemo](https://www.saucedemo.com/) across multiple browsers using BrowserStack or manual testing.

---

 Tools & Setup:
- *Device Used*: Android smartphone
- *Browsers Tested*: Chrome, Brave (mobile)
- *Testing Method*: Manual testing
- *Reason for Limitation*: 
  - No access to desktop browsers like Firefox, Safari, or Edge.
  - BrowserStack free session expires too quickly on mobile before full test is completed.

---

Browsers Tested

| Browser | Device | Result        | Observations                |
|---------|--------|----------------|-----------------------------|
| Chrome  | Android | ✅ Working      | Login successful, no UI bugs |
| Brave   | Android | ✅ Working      | All UI elements worked well |
| Firefox | –      | ❌ Not Tested   | No access                   |
| Edge    | –      | ❌ Not Tested   | Not on Android              |
| Safari  | –      | ❌ Not Applicable | Not on Android              |

---

 Test Performed:
- Used standard_user and password secret_sauce
- Login successful
- Observed layout, responsiveness, and UI behavior
- Compared performance between Chrome and Brave

---

Limitations:
- Could not access other browsers like Firefox, Safari, and Edge due to device/browser limitations
- BrowserStack session expired before running full cross-browser scripts

---

 Conclusion:
Login functionality and basic UI are consistent across Chrome and Brave (Android). Limited cross-browser testing completed using available tools.
