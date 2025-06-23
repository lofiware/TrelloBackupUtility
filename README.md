# TrelloBackupUtility
CSV Export with Comments &amp; Attachments
![Scanned by Snyk](https://img.shields.io/badge/Snyk-Scanned-brightgreen?logo=snyk)

# Trello Backup Tool

[![Last Commit](https://img.shields.io/github/last-commit/lofiware/TrelloBackupUtility)](https://github.com/lofiware/TrelloBackupUtility)
[![Stars](https://img.shields.io/github/stars/lofiware/TrelloBackupUtility?style=social)](https://github.com/lofiware/TrelloBackupUtility/stargazers)

---

## 🧭 Introduction

**Trello Backup Utility** is a lightweight desktop utility designed to automatically back up your Trello boards, cards, comments, attachments, and metadata to CSV files for offline storage and long-term archiving.

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
Latest release: [trello-backup-tool-v1.0.0.exe](https://github.com/lofiware/TrelloBackupUtility/releases)

No Python installation required. Download and run.

---

## ♻️ Restores
Currently, this tool does not support restoring data to Trello.

Backups are structured in a way that makes partial manual recreation easy if necessary:

Each board gets its own folder

Each card is represented as a row with metadata

Attachments are downloaded into corresponding card subfolders

Comments, checklists, and labels are stored per card

Planned restore options are in the Roadmap.

---

## 🛣️ Roadmap
*Add automated scheduled backups

*Implement restore-to-Trello via API (optional)

*Support for JSON format alongside CSV

*Cloud backup integrations (Dropbox, GDrive, S3)

*Command-line options and headless mode

*Multi-user or team support

See Issues for more.

---

## 💖 Support Us
This project is developed with care.

If you find it useful:

⭐ Star the repo

🐛 Report bugs or suggest features

🤝 Contribute code or documentation

☕ Buy me a coffee (optional)(not yet - keep your money)
