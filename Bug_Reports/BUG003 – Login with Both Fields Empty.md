# Bug Report - BUG003

**Bug ID:** BUG003  

**Title:** Login attempt with both username and password fields empty  

**Module / Feature:** Login Page  

**Environment:**  
- Browser: Chrome  
- OS: Windows 10  
- URL: https://demoqa.com/login  

**Severity:** Medium  
**Priority:** Medium  

---

## Description
When both Username and Password fields are left empty, the system only highlights the fields in red but does not display the expected error message.

---

## Steps to Reproduce
1. Open Login page  
2. Leave both Username and Password fields empty  
3. Click Login  

---

## Expected Result
Error message: "Username & Password required" should appear.

---

## Actual Result
Only red field highlight appeared. No error message text is displayed.

---

## Status
Open ❌

---

## Screenshot
`../Screenshots/BUG003_Login_Both_Fields_Empty.png`
