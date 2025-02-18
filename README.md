🚀 Duplicate File Remover
A Python-based utility to scan directories, detect duplicate files using MD5 hashing, and delete redundant copies to free up storage.

📌 Features
Recursively scans directories for duplicate files
Uses MD5 hashing to ensure accurate duplicate detection
Displays duplicate files before deletion
Automated file removal while keeping one original copy
Tracks execution time for performance insights

🔧 Installation
Ensure you have Python installed, then clone the repository:
git clone https://github.com/yourusername/Duplicate-File-Remover.git
cd Duplicate-File-Remover

▶️ Usage
Run the script from the terminal:
python duplicate_remover.py <directory_path>

📖 Command-line Options
-h or -H → Display help message
-u or -U → Show usage instructions

🛠️ Requirements
Python 3.x
os, sys, hashlib, time (built-in modules)

⚡ Example
python duplicate_remover.py /path/to/directory
