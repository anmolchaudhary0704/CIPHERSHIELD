# 🔐 CipherShield

### Secure Authentication, Encryption & Digital Signature Framework

CipherShield is a Flask-based cybersecurity application that provides secure file encryption, decryption, digital signature generation, signature verification, and user authentication through an intuitive web interface.

The project demonstrates the practical implementation of cryptographic concepts including RSA public-key cryptography, digital signatures, hashing, secure file handling, and session-based authentication. It serves as a hands-on framework for understanding modern security mechanisms used in secure systems and applications.

---

## 🚀 Features

### 🔑 Authentication System

* Secure user login
* Session management
* Protected application routes
* Access control mechanism

### 🔒 File Encryption & Decryption

* Encrypt files before storage or sharing
* Decrypt encrypted files securely
* User-controlled encryption key support
* File confidentiality protection

### ✍️ Digital Signatures

* RSA-based digital signature generation
* Signature verification using public keys
* Authenticity validation
* Non-repudiation support

### 🛡️ Integrity Verification

* Custom hashing implementation
* File integrity checks
* Tamper detection mechanism

### 📂 Secure File Management

* File upload functionality
* Secure file processing
* Encrypted file generation
* Signature file generation

---

## 🛠️ Technology Stack

### Backend

* Python
* Flask

### Frontend

* HTML5
* CSS3
* JavaScript

### Security Concepts

* RSA Cryptography
* Digital Signatures
* Public & Private Key Encryption
* Hash Functions
* Authentication & Authorization

---

## 📂 Project Structure

```text
CipherShield/
│
├── app.py
├── keygen.py
├── README.md
│
├── keys/
│   └── keys
│
├── static/
│   └── static
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── encrypt_decrypt.html
│   └── sign_verification.html
│
└── uploads/
    └── uploads
```

---

## ⚙️ Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/anmolchaudhary0704/CipherShield.git
cd CipherShield
```

### Create a Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux / macOS:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install flask cryptography pycryptodome
```

### Generate RSA Keys

```bash
python keygen.py
```

### Start the Application

```bash
python app.py
```

### Open in Browser

```text
http://127.0.0.1:5000
```

---

## 🔄 Application Workflow

```text
User Login
     │
     ▼
Authentication
     │
     ▼
Dashboard
     │
 ┌───┴─────────────┐
 │                 │
 ▼                 ▼
Encrypt File     Sign File
 │                 │
 ▼                 ▼
Encrypted File   Signature
 │                 │
 ▼                 ▼
Decrypt File    Verify Signature
```

---

## 🔐 Security Modules

### Authentication Module

Manages user login, session creation, and protected access to application features.

### Encryption Module

Encrypts files using cryptographic techniques to ensure confidentiality.

### Decryption Module

Restores encrypted files to their original form using the appropriate key.

### Digital Signature Module

Generates RSA-based signatures to verify file authenticity.

### Verification Module

Validates digital signatures and ensures data integrity.

---

## 🎯 Learning Outcomes

This project demonstrates:

* Secure Web Application Development
* Cryptography Fundamentals
* RSA Public-Key Infrastructure
* Digital Signature Implementation
* Session-Based Authentication
* File Security Techniques
* Secure File Handling
* Flask Backend Development

---

## 🔮 Future Enhancements

* AES-256 Encryption
* JWT Authentication
* Multi-Factor Authentication (MFA)
* User Registration System
* Database Integration
* Cloud Storage Support
* Audit Logging
* Role-Based Access Control (RBAC)
* Secure Key Management

---

## 👨‍💻 Contributors

* Tanya Mangla
* Anmol Kumar
* Prachi Kaintura
* Pragya Thapliyal

---

## 📜 License

This project is developed for educational, research, and learning purposes.

---

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.

Your support helps improve and maintain the project.
