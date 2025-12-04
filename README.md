# Enhancing Security in Messaging Applications

This project demonstrates security features for a messaging application across nine tasks, including AES encryption, end-to-end encryption, SRTP-based voice protection, secure file transfer, authentication with 2FA, TLS secure communication, privacy-by-design mechanisms, monitoring, and user education.

---

## 📁 Repository Structure

task1_aes_demo/
task2_e2ee/
task3_srtp/
task4_file_transfer/
task5_auth/
task6_tls/
task7_privacy/
task8_monitoring/
task9_user_education/
requirements.txt
README.md

---

## ⚙️ How to Set Up

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

▶️ Example
cd task1_aes_demo
python3 encrypt_demo.py
🔧 Technologies Used

AES (EAX / GCM)

RSA Key Exchange

HMAC

bcrypt hashing

pyotp (OTP)

TLS certificates (OpenSSL)

JSON-based monitoring

Python 3.11+ on Kali Linux

🔐 Notes

No private keys or sensitive data are stored.
TLS private key is not included for security.
openssl req -x509 -newkey rsa:2048 -nodes -keyout server_key.pem -out server_cert.pem -days 365
