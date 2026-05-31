# 🔐 Password Strength Analyzer

A simple Python-based **Password Strength Analyzer** that evaluates the security level of a user-entered password based on multiple criteria such as length, uppercase letters, lowercase letters, numbers, and special characters.

## 📌 Features

✅ Checks password length  
✅ Detects uppercase and lowercase letters  
✅ Verifies presence of numbers  
✅ Identifies special characters  
✅ Classifies password strength:
- Weak 🔴
- Medium 🟡
- Strong 🟢

✅ Suggests improvements for weak passwords

## 🛠️ Technologies Used

- Python
- Regular Expressions (`re` module)

## 📂 Project Structure

```text
Password-Strength-Analyzer/
│── password_strength_analyzer.py
│── README.md
```

## 🚀 How It Works

The program checks the password against the following conditions:

1. Minimum password length (8 characters)
2. Presence of uppercase letters
3. Presence of lowercase letters
4. Presence of numbers
5. Presence of special characters

Based on these checks, the password is classified as:

| Score | Strength |
|--------|----------|
| 0 - 2  | Weak |
| 3 - 4  | Medium |
| 5      | Strong |

## ▶️ Installation & Usage

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/password-strength-analyzer.git
```

### Step 2: Navigate to Project Folder

```bash
cd password-strength-analyzer
```

### Step 3: Run the Program

```bash
python password_strength_analyzer.py
```

## 💻 Example Output

### Weak Password Example

```text
Enter your password: 12345

Password Strength: Weak

Suggestions to improve password:
- Use at least 8 characters
- Add at least one uppercase letter
- Add at least one lowercase letter
- Add at least one special character
```

### Strong Password Example

```text
Enter your password: Hello@123

Password Strength: Strong
Your password is secure!
```

## 🔒 Cybersecurity Concepts Used

- Password Security
- Authentication Basics
- Strong Password Policies
- Secure Password Practices

## 🎯 Future Improvements

- GUI Interface using Tkinter
- Password breach detection
- Password entropy calculation
- Generate stronger password suggestions

## 👨‍💻 Author

**Lakshita Mangal**
---

⭐ If you found this project useful, consider giving it a star!
