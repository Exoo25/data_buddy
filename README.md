# 📂 DataBuddy – Universal Data Converter & Encryptor

A lightweight Python library to **convert, encrypt, and decrypt** data files directly from your scripts or CLI.  
Perfect for quick **JSON ⇆ YAML ⇆ CSV ⇆ XLSX** conversions and password-based encryption of sensitive files.

> **The best thing:**  
> No GUI, no fluff — just simple Python functions and a clean command-line workflow.

---

## 🚀 Features

- 🔄 Convert between `JSON`, `YAML`, `CSV`, and `XLSX`
- 🔐 Encrypt & Decrypt any file with a password (Fernet AES)
- ⚙️ Minimal, clear – one-liner conversions
- 📁 Works cross-platform (Windows, macOS, Linux)
- 📦 Lightweight dependencies: `pandas`, `pyyaml`, `openpyxl`, `cryptography`

---

## 📸 Usage

```python
import databuddy as db

# Convert YAML → JSON
db.convert("data.yml", "data.json")

# CSV → XLSX
db.convert("records.csv", "records.xlsx")

# Encrypt file
db.encrypt("data.json", password="mysecret")

# Decrypt file
db.decrypt("data.json.enc", password="mysecret", out_path="data_dec.json")
```
##📦 Installation 
```bash
cd <path_to_your_project>
git clone https://github.com/Exoo25/databuddy.git
cd databuddy
pip install -r requirements.txt
```
> ##⚠️ Tip:
> Always keep your password safe. Losing it means your encrypted files cannot be recovered.
