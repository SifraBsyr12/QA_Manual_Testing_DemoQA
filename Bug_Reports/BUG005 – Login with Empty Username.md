# Bug Report - BUG005

**Bug ID:** BUG005  

**Title:** Login attempt with empty username field  

**Module / Feature:** Login Page  

**Environment:**  
- Browser: Chrome  
- OS: Windows 10  
- URL: https://demoqa.com/login  

**Severity:** Medium  
**Priority:** Medium  

---

## Description
When the Username field is left empty, the system highlights the field but does not display the expected error message.

---

## Steps to Reproduce
1. Open Login page  
2. Leave Username field empty  
3. Enter valid Password  
4. Click Login  

---

## Expected Result
Error message: "Username required" should appear.

---

## Actual Result
Username field highlighted in red. No error message text displayed.

---

## Status
Open ❌

---

## Screenshot
`../Screenshots/BUG005_Login_Empty_Username.png`
