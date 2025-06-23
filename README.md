# TrelloBackupUtility
CSV Export with Comments &amp; Attachments

# Trello Backup Tool

[![Last Commit](https://img.shields.io/github/last-commit/lofiware/TrelloBackupUtility)](https://github.com/lofiware/TrelloBackupUtility)
[![Stars](https://img.shields.io/github/stars/lofiware/TrelloBackupUtility?style=social)](https://github.com/lofiware/TrelloBackupUtility/stargazers)

---

## 🧭 Introduction

**Trello Backup Tool** is a lightweight desktop utility designed to automatically back up your Trello boards, cards, comments, attachments, and metadata to CSV files for offline storage and long-term archiving.

Built with Python, the tool is cross-platform and ideal for both personal and organizational use.

---

## 🎯 Purpose / Use Case

Trello does not natively offer full offline backup options with attachments and comments. This tool was developed to:

- Archive active workspaces or boards
- Ensure project continuity if Trello access is lost
- Provide a CSV-based snapshot for audits, records, or migration
- Enable scheduled or manual backups
- Store backups securely in your own folders
- Avoid vendor lock-in

---

## ⚙️ Setup / Configuration

### ✅ Requirements
- Python 3.8+
- Trello API key & token (stored securely using `keyring`)
- GUI or CLI available (depending on version)

### 🔧 First-Time Setup
1. Clone the repository or download the `.exe` (see [Downloads](#downloads))
2. Run the app and follow the authentication prompts
3. Choose which Trello boards to back up
4. Select an output folder (remembered for next time)
5. Customize options like:
   - Include closed cards
   - Include attachments
   - Save log file

---

## 📦 Downloads

### 🖥️ Windows Executable
Latest release: [trello-backup-tool-v1.0.0.exe](https://github.com/YOUR_USERNAME/trello-backup-tool/releases)

No Python installation required. Download and run.

### 🐍 Python Users
```bash
git clone https://github.com/YOUR_USERNAME/trello-backup-tool.git
cd trello-backup-tool
pip install -r requirements.txt
python main.py
