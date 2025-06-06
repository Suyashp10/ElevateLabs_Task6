# 🔐 Task 6 – Password Strength Evaluation

## 🧠 Objective
The goal of this task was to understand what makes a password strong and how password complexity directly impacts security. By creating and evaluating multiple passwords using online tools, I gained practical insights into password best practices and common weaknesses.

---

## 🛠 Tools Used
- [PasswordMeter](https://www.passwordmeter.com/)
- [NordPass Password Strength Checker](https://nordpass.com/password-strength-checker/)
- [whatismyipaddress.com](https://whatismyipaddress.com/) (used in next tasks)
- Manual analysis

---

## 📂 Files Included
```
.
├── README.md
├── passwords.txt                 # Sample passwords tested
├── evaluation_results.csv        # Password analysis and feedback
└── screenshots/                  # Screenshots of password strength results
```

---

## 🔑 Passwords Evaluated

| Password       | Complexity   | Strength (%) | Notes                                |
|----------------|--------------|--------------|--------------------------------------|
| `h3ll0123`      | Medium       | 55%          | Lowercase with numbers               |
| `suyash`        | Weak         | 30%          | Simple name, all lowercase           |
| `h3\0_123`     | Medium-High  | 65%          | Symbols, numbers, but no uppercase   |
| `Suyash`        | Weak         | 35%          | Capitalized name, no complexity      |
| `[-]3\0_123`   | Strong       | 80%          | Complex use of symbols & numbers     |

📸 Screenshots available in the `screenshots/` folder.

---

## 💡 Key Learnings
- Passwords with a mix of uppercase, lowercase, numbers, and symbols are significantly stronger.
- Length plays a major role in resisting brute force attacks.
- Dictionary words and names (even with slight modifications) are still considered weak.
- Passphrases (longer, uncommon combinations) offer better security than short complex passwords.
- Password managers and multi-factor authentication greatly enhance password security.

---

## 📚 Concepts Covered
- Password entropy and complexity
- Brute force and dictionary attacks
- Password manager usage
- Best practices for creating strong, secure passwords

---

## 📸 Screenshots
All evaluation screenshots are stored in the `/screenshots` folder and named corresponding to the tested passwords.

---

## ✅ Status
✅ Task completed successfully.  
🗃️ Submitted via GitHub as part of Elevate Labs Cyber Security Internship.
