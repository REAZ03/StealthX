🛡️ StealthX – Cyber Password Analysis Toolkit

StealthX is a self-contained cybersecurity toolkit built for analysing password strength and demonstrating real-world cracking techniques using offline tools like John the Ripper.
Designed for learning, auditing, and understanding password security in a safe offline environment.

🚀 Features
🔍 Password Strength Analysis

Regex-based validation (length, symbols, digits, uppercase, lowercase)

ZXCVBN scoring and realistic crack-time estimation

Entropy calculation in bits

Suggestions to improve weak passwords

🧪 Attack Simulation (Real John the Ripper)

Dictionary attack using rockyou.txt

Incremental brute-force mode

Hybrid rule-based attack

Real hash generation using OpenSSL md5crypt

Live “cracking in progress” visual output

Summary of time & results

🔐 Password Utility Tools

Secure random password generator

Strong password recommendation engine

Password history summary

🖥️ Interface & Experience

Cinematic red ASCII banner (“STEALTHX”)

Clean, centered UI using rich

Zero internet usage — fully offline

Runs on any Linux system without setup

📁 Project Structure
StealthX/
 ├── StealthX.py              # Main program
 ├── RUN.sh                   # Easy launcher script
 ├── zxcvbn/                  # Local ZXCVBN module (portable)
 ├── checker.py               # Older logic (optional)
 ├── demo_hashes.txt
 ├── attack_hash.txt
 ├── password_checker.log
 ├── README.md
 └── source/


Completely portable — no pip installation required.

▶️ How to Run StealthX

Extract the ZIP:

unzip StealthX_Project.zip
cd StealthX


Make launcher executable:

chmod +x RUN.sh


Run the toolkit:

./RUN.sh


Everything works offline — all dependencies included.

🧩 Dependencies Inside the Project

rich (for UI)

colorama (for terminal colors)

zxcvbn (included locally)

OpenSSL (system default)

John the Ripper (pre-installed in Kali Linux)

No external installation required.

👨‍💻 Developer
《  Developer: Pathan Rakib 》
