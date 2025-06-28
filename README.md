# 🗂️ Automated Backup Script with Logging

A Python script that automates the process of backing up files or folders by compressing them into timestamped ZIP archives. Each backup is logged for reference or audit purposes.


## ✨ Features

- 📦 Automatic ZIP backups of files/folders  
- 🕒 Timestamps added to filenames  
- 📝 Log file (`backup.log`) with detailed backup info  
- ⚙️ Simple, lightweight, and fully customizable

## 🛠 Technologies Used

- Python 3.x  
- **Standard Library Only** — no external packages required


## 🚀 Getting Started

### 1. Create and Activate a Virtual Environment (Optional)

```bash
python -m venv .venv
```
windows:  `.venv\Scripts\activate`    or    Linux/Mac:   `source .venv/bin/activate`

### 2.Run the Script
```bash
python backup_script.py
```

### 📦 Requirements
No external dependencies — uses only built-in Python modules:
* os
* shutil
* zipfile
* datetime
* logging

