# Week 2 – Cross-Site Scripting (XSS) Assessment

## Internship
Cybersecurity Internship  
**DevelopersHub Corporation**

---

## Objective
The objective of Week-2 was to identify and exploit a Cross-Site Scripting (XSS) vulnerability in a vulnerable web application and understand its impact.

---

## Target Application
- **OWASP Juice Shop**
- Deployed locally using Node.js
- URL: http://localhost:3000

---

## Vulnerability Identified
- **Type:** Reflected Cross-Site Scripting (XSS)
- **Affected Component:** Search functionality

---

## Payload Used
```html
<img src=x onerror=alert(1)>
