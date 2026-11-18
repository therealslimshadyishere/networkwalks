# Week 3 Lab: Hash Extraction & Password Cracking (John the Ripper)

This repository contains screenshot documentation and execution results from a cybersecurity lab focused on cryptographic hash extraction, PDF password protection analysis, and offline password auditing using **John the Ripper** and related cracking utilities.

---

## 📁 Repository Contents

All lab evidence and command-line outputs are organized inside the `w3/` directory:

| File | Description |
| :--- | :--- |
| `w3/hash.png` | Initial hash generation, format identification, or target hash capture. |
| `w3/cracker1.png` | Initial setup and wordlist/rule configuration for the password cracker. |
| `w3/cracker2.png` | Active cracking session progress and brute-force/dictionary attack execution. |
| `w3/cracker3.png` | Final cracked credentials output and session summary. |
| `w3/nw_pdf.png` | Creation or inspection of a password-protected PDF target file. |
| `w3/pdf1.png` | Extracting the password hash from the protected PDF (e.g., via `pdf2john`). |
| `w3/pdf2.png` | Verifying the extracted PDF hash structure and encoding. |
| `w3/pdf3.png` | Additional PDF encryption metadata and security parameters. |
| `w3/john_pdf1.png` | Running John the Ripper against the extracted PDF hash. |
| `w3/john_pdf2.png` | Monitoring John the Ripper cracking progress and wordlist matching. |
| `w3/john_pdf3.png` | Successfully recovered PDF password (`john --show` output). |

---

## 🛠️ Tools & Concepts Covered

* **Tools:** John the Ripper (`john`), `pdf2john`, standard Linux CLI utilities.
* **Techniques:**
  * Extracting password hashes from encrypted PDF documents.
  * Identifying hash formats and encryption algorithms.
  * Performing dictionary and rule-based offline password attacks.
  * Auditing password complexity and demonstrating the risks of weak credentials.

---

## 🚀 General Workflow Demonstrated

1. **Target Preparation & Hash Identification (`hash.png`, `nw_pdf.png`):** Inspecting target hashes and creating/analyzing password-protected PDF files.
2. **Hash Extraction (`pdf1.png` – `pdf3.png`):** Converting protected PDF metadata into a crackable hash string using `pdf2john`.
3. **Password Auditing (`cracker1.png` – `cracker3.png`, `john_pdf1.png` – `john_pdf3.png`):** Executing dictionary attacks with John the Ripper and verifying recovered plaintext passwords.

---

## ⚠️ Disclaimer

> **For Educational Purposes Only:** The techniques and tools documented in this repository were executed in a controlled lab environment for educational and defensive security auditing purposes. Always obtain explicit authorization before testing or auditing systems and files you do not own.