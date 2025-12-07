# Gmail Example Credential Generator (Termux)

This Termux script demonstrates how to generate an example Gmail login entry
using a placeholder email and a randomly generated 20-character password.

⚠️ **Important Notice**
- This does *not* create a real Google Gmail account.
- This does *not* log in to Google.
- The credentials are **examples only** and stored locally on your device.

---

## 📧 Example Gmail Login

- **Email:** JohnDoe22@gmail.com  
- **Password:** Randomly generated (20 characters)

---

## 📦 Install Requirements (Termux)

```bash
pkg update -y && pkg upgrade -y
pkg install openssl -y
pkg install nano -y
