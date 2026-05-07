🚀  File Encryption Software Built Using Python

SecureVault Pro is a professional cybersecurity-based desktop application that allows users to securely encrypt and decrypt files using advanced AES-256 encryption techniques.

</div>
📌 Features

✅ AES-256 File Encryption
✅ Secure Password Protection
✅ Folder Encryption Support
✅ Drag & Drop File Selection
✅ Modern Dark UI
✅ Password Generator
✅ File Integrity Verification
✅ Fast Encryption Engine
✅ Multithreading Support
✅ Export Encryption Logs

🖼️ Screenshots

🔐 Login Screen

<img width="857" height="685" alt="image" src="https://github.com/user-attachments/assets/c6de4e58-ebd4-40ee-8d90-7198c1707863" />


📂 Encryption Dashboard

<img width="1042" height="681" alt="image" src="https://github.com/user-attachments/assets/0252c867-b6fa-40b8-8fd3-d8dd27091b4f" />


🔓 File Decryption

<img width="922" height="707" alt="image" src="https://github.com/user-attachments/assets/c4aac993-0e91-4d47-86e6-3ff7963ce9ea" />


⚙️ Settings Panel

<img width="925" height="690" alt="image" src="https://github.com/user-attachments/assets/b846c942-c9a0-4aeb-84fe-5191e5459d09" />


📊 Encryption Progress

<img width="927" height="691" alt="image" src="https://github.com/user-attachments/assets/b46f4b4a-0149-4c8e-84c6-f66d4bc3e552" />



⚙️ Tech Stack

Technology	Purpose
Python	Core Programming
PyQt	Desktop GUI
PyCryptodome	AES Encryption
Threading	Performance
SQLite	Log Storage


📂 Project Structure

securevault-pro/
│
├── assets/
├── screenshots/
├── encrypted_files/
├── decrypted_files/
├── keys/
│
├── main.py
├── encrypt.py
├── decrypt.py
├── password_manager.py
├── gui.py
├── logger.py
│
├── requirements.txt
├── README.md
└── LICENSE


🚀 Installation

1️⃣ Clone Repository
git clone https://github.com/yourusername/securevault-pro.git
cd securevault-pro

2️⃣ Create Virtual Environment
python -m venv venv

3️⃣ Activate Environment
Windows
venv\Scripts\activate
Linux/Mac
source venv/bin/activate

4️⃣ Install Requirements
pip install -r requirements.txt

▶️ Run Application
python main.py
📦 requirements.txt
pycryptodome
PyQt5
pillow


🔐 Encryption Workflow

Select File
     ↓
Generate Secure Key
     ↓
AES-256 Encryption
     ↓
Save Encrypted File


🧠 Core Functionalities

🔒 File Encryption

Encrypts files securely using AES-256 algorithm.

🔓 File Decryption

Decrypts files only with correct password.

🔑 Password Generator

Creates strong random passwords.


📁 Folder Protection

Supports bulk folder encryption.



💻 Encryption Code
from Crypto.Cipher import AES
from Crypto.Random import get_random_bytes

key = get_random_bytes(32)

cipher = AES.new(key, AES.MODE_EAX)

with open("sample.txt", "rb") as file:
    data = file.read()

ciphertext, tag = cipher.encrypt_and_digest(data)

print("File Encrypted Successfully")



📈 Future Enhancements

Cloud Backup
USB Auto Encryption
Two-Factor Authentication
Biometric Login
Secure File Sharing
Dark/Light Themes


🛡️ Security Features

✅ AES-256 Encryption
✅ Password Hashing
✅ Secure Key Storage
✅ Integrity Verification
✅ Session Protection


📜 License

This project is licensed under the MIT License.

👨‍💻 Author
Praveen

🚀 Passionate Python Developer
🔐 Cybersecurity Enthusiast
💻 Advanced Software Builder

⭐ Support

If you like this project:

🌟 Star the repository
🍴 Fork the project
📢 Share with others
