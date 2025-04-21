🚀 SecureHealthCloud: Confidential DBaaS for Healthcare
SecureHealthCloud is a lightweight, Flask-based web application designed to safeguard sensitive healthcare data using end-to-end encryption. Built as part of a team project, it enables secure storage, retrieval, and controlled access to health records on the cloud—ensuring compliance with data privacy standards such as HIPAA.

🔐 Key Features
AES-CBC encryption via Fernet to protect sensitive fields (Age, Gender, Health History)

Role-based access control (Groups H & R) with conditional attribute visibility

Encrypted password storage with authentication-based access

Digital signature verification to ensure data integrity

MySQL backend for reliable, scalable data storage

HTML/CSS front-end with Flask API middleware

🧱 Tech Stack
Python + Flask

MySQL

Fernet (Cryptography Library)

HTML/CSS (Frontend)

👥 Team Contributions
Ratan: UI Design, User Authentication, Documentation

Manikanta: Encryption Algorithms, DB Architecture, Research, Documentation

⚠️ Limitations
Sensitive reliance on single encryption key (Fernet)

Flask lacks built-in advanced security features

Requires careful encryption key management and token handling
