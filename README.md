# Password Cracking & Credential Attack Suite

A cybersecurity project focused on ethical password auditing, credential analysis, and password strength testing using Kali Linux tools and Python scripts.

## 🚀 Features

* Dictionary-based password testing
* Linux shadow hash extraction
* Windows SAM hash extraction
* Brute-force attack simulation
* Password strength & entropy analysis
* Security audit report generation

## 🛠️ Tools & Technologies

* Python
* Kali Linux
* John the Ripper
* Hashcat
* Samdump2
* Passlib

## 📂 Project Workflow

1. Setup Kali Linux lab environment
2. Generate password wordlists
3. Extract Linux password hashes
4. Extract Windows SAM hashes
5. Perform dictionary attack simulation
6. Analyse password strength
7. Generate security audit report

## ⚙️ Installation

```bash
sudo apt update
sudo apt install john hashcat python3-pip python3-passlib
```

## ▶️ Usage

### Run Dictionary Generator

```bash
python3 dictionary_generator.py
```

### Crack Hashes with John

```bash
john --format=NT --wordlist=wordlist.txt windump
```

### Show Cracked Passwords

```bash
john --show --format=NT windump
```

### Password Strength Analysis

```bash
python3 password_strength.py
```

## 📊 Learning Outcomes

* Understanding password hashing mechanisms
* Ethical credential auditing techniques
* Password attack methodologies
* Secure password policy implementation
* Red Team vs Blue Team concepts

## ⚠️ Disclaimer

This project is created strictly for educational and ethical cybersecurity learning purposes only. Do not use these techniques on unauthorized systems.

## 👩‍💻 Author

**Sakshi Maruti Nalawade**
Institute: Unified Mentor
