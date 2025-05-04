
COMPANY: CODTECH IT SOLUTIONS

NAME: PITTA MEGHANA

INTERN ID: CT12MLF

DOMAIN: CYBER SECURITY AND ETHICAL HACKING

BATCH DURATION: FEBRUARY 5th, 2025 to MAY 5th, 2025

MENTOR NAME: NEELA SANTHOSH KUMAR

 FILE INTEGRITY CHECKER
    A simple and efficient tool to verify the integrity of files by generating and comparing hash values, ensuring that files have not been altered, corrupted, or tampered with.

📝 About the Project
  The File Integrity Checker is designed to ensure that a file’s content remains unchanged over time or during transfers. It does this by generating cryptographic hash values (like SHA-256) and comparing them to previously recorded values. This helps detect unauthorized changes, corruption, or tampering.
  
  This project was built as part of my internship to demonstrate real-world application of hashing algorithms in file security and verification.

🧰 Tech Stack
    🐍 Python 3.x
    
    📦 hashlib for hash generation
    🖥️ Command-line interface (CLI)  
    🗃️ File handling and I/O

✨ Features
    1.Generate hash of any file using SHA-256
    2.Store original hash for future comparisons
    3.Compare current hash with saved hash to detect modifications
    4.CLI-based for ease of use and automation
    5.Supports multiple file types: .txt, .pdf, .png, .exe, etc.

🚀 Getting Started
    Prerequisites
    Make sure Python is installed on your machine:
    
    bash
    Copy
    Edit
    python --version
    Installation
    Clone the repository:
    
    bash
    Copy
    Edit
    git clone https://github.com/your-username/file-integrity-checker.git
    cd file-integrity-checker
    (Optional) Create a virtual environment and activate it:
    
    bash
    Copy
    Edit
    python -m venv venv
    source venv/bin/activate  # For Linux/Mac
    venv\Scripts\activate     # For Windows
    No external libraries need to be installed.

▶️ Usage
    GENERATE AND SAVE HASH 
    
      python file_checker.py --generate yourfile.txt
      
      This command will: 1. Calculate the SHA-256 hash
                         2. Store it in hashes.json
    
    VERIFY FILE INTEGRITY
  
      python file_checker.py --verify yourfile.txt
     
      This will: 1.Recalculate the hash
                 2.Compare it with the stored value
                 3.Print whether the file has been modified or not
    
    HELP
    
      python file_checker.py --help




