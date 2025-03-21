# 🔏 Digital Signature System

## 📌 Project Overview

The **Digital Signature System** ensures the **authenticity, integrity, and security** of digital documents using **SHA-256 hashing** and **RSA encryption**. It allows users to sign and verify documents, ensuring they remain unaltered.

## ✨ Features

- ✅ **Secure Hashing (SHA-256):** Creates a cryptographic hash of documents.  
- ✅ **Digital Signature Generation:** Signs the document using RSA encryption.  
- ✅ **Signature Verification:** Confirms authenticity and detects modifications.  
- ✅ **Base64 Encoding Support:** Provides encoded versions of signatures.  
- ✅ **Comprehensive Logging:** Logs all signing and verification activities.  

---

## 📁 Project Structure

```
digital-signature-system/
│── images/                          # Contains project-related images
│── output/                          # Stores generated outputs
│   ├── keys/                        # RSA Key Pair storage
│   │   ├── confidential_document_modified.txt
│   │   ├── confidential_document.txt
│   │   ├── confidential_document.txt.sig
│   │   ├── confidential_document.txt.sig.b64
│   ├── secret_plans.pdf
│   ├── secret_plans.pdf.sig
│   ├── secret_plans.pdf.sig.b64
│   ├── signature_info.log           # Logs signing & verification activities
│── report/                          # Stores reports
│   ├── digital_signature_system.pdf
│── .gitignore                        # Ignores unnecessary files in Git
│── digital_sig_sys.ipynb             # Jupyter Notebook implementation
│── README.md                         # Project documentation
```

---

## 🛠️ Installation & Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/mnh-stack/digital-signature-system.git
cd digital-signature-system
```

### **2️⃣ Create a Virtual Environment (Recommended)**
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

---

## 🚀 Usage Guide

### **🔹 Running the Digital Signature System**

Since all functionality is implemented in **Jupyter Notebook**, follow these steps:

1. **Launch Jupyter Notebook**  
   ```bash
   jupyter notebook
   ```
2. **Open `digital_sig_sys.ipynb`**
3. **Run all cells sequentially** to:  
   - Generate keys  
   - Sign documents  
   - Verify signatures  
   - Detect modifications  

---

## 🔐 Security Considerations

- **SHA-256 is collision-resistant**, ensuring secure hashing.  
- **RSA encryption ensures authenticity**, preventing unauthorized alterations.  
- **Any modification to the document** results in verification failure.  

---

## 📜 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 🤝 Contributing

1. **Fork the repository.**  
2. **Create a feature branch:**  
   ```bash
   git checkout -b feature-branch
   ```
3. **Commit changes:**  
   ```bash
   git commit -m "Added new feature"
   ```
4. **Push to your fork:**  
   ```bash
   git push origin feature-branch
   ```
5. **Submit a Pull Request.**

---

## 📧 Contact

👤 **Muhammad Nouman Hafeez**  
📍 **FAST NUCES, Islamabad**  
📧 [noumanhafeez.nh11@gmail.com](mailto:noumanhafeez.nh11@gmail.com)  
🔗 [GitHub Profile](https://github.com/mnh-stack)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/noumanhafeez11nh/)

---