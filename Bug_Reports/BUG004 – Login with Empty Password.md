# Bug Report - BUG004

**Bug ID:** BUG004  

**Title:** Login attempt with empty password field  

**Module / Feature:** Login Page  

**Environment:**  
- Browser: Chrome  
- OS: Windows 10  
- URL: https://demoqa.com/login  

**Severity:** Medium  
**Priority:** Medium  

---

## Description
When the Password field is left empty, the system highlights the field but does not display the expected error message.

---

## Steps to Reproduce
1. Open Login page  
2. Enter valid Username  
3. Leave Password field empty  
4. Click Login  

---

## Expected Result
Error message: "Password required" should appear.

---

## Actual Result
Password field highlighted in red. No error message text displayed.

---

## Status
Open ❌

---

## Screenshot
`../Screenshots/BUG004_Login_Empty_Password.png`
