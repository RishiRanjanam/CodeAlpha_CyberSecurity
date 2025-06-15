# Task 3: Secure Coding Review

## 📌 Objective

This task involves reviewing insecure code for vulnerabilities and recommending secure alternatives. The purpose is to build awareness of secure coding practices and prevent common exploits in application development.

---

## 📂 Files Included

| File Name              | Description                                      |
|------------------------|--------------------------------------------------|
| `vulnerable_code.py`   | Contains an intentionally insecure Python script |
| `secure_code_review.md`| A detailed report identifying issues and solutions|

---

## 🔍 What Was Reviewed

The vulnerable code demonstrates poor practices such as:
- Hardcoded credentials
- Use of dangerous functions like `exec()`
- No input validation

These can lead to security flaws such as:
- Code injection
- Credential leaks
- Unauthorized access

---

## ✅ Secure Coding Recommendations

- Avoid hardcoding sensitive information
- Replace `eval()` or `exec()` with safer alternatives
- Sanitize and validate all user inputs
- Store secrets using environment variables or config files
- Follow the OWASP Top 10 guidelines

---

## 🛠️ Tools You Can Use for Review

While this task was done manually, here are some tools used in the industry:
- **Bandit** (Python static analysis)
- **SonarQube**
- **PyLint Security Plugin**
- **Semgrep**

---

## 💡 Key Takeaways

Secure coding is not optional — it’s essential. Even simple applications should be written defensively to protect both users and data. This review serves as a reminder to think like an attacker, and code like a defender.

---

## 📸 Screenshots / Demo (Optional)

You can add screenshots here showing your review process, code before and after, or a walkthrough video link.

---

> **Internship Note:** This task is part of CodeAlpha's Cyber Security Internship. Completing three tasks (like this one) is mandatory to receive the internship certificate.

