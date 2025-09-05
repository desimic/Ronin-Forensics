# Ronin Crypto Forensics Investigation Repository

This GitHub repo is structured for a full blockchain forensic investigation and OSINT automation pipeline for the Ronin Network exploit attributed to the Lazarus Group.

## 📁 Folder Structure

- `/reports` - Word/PDF incident reports, threat actor profiles, evidence logs
- `/diagrams` - Graph exports from Crystal, Maltego, and wallet cluster diagrams
- `/automation` - Python scripts for SpiderFoot automation, JSON ingest tools
- `/.github/workflows` - CI/CD actions to automate analysis, scans, and linting

## ⚙️ Visual Studio Code Setup

1. Open Visual Studio Code
2. Select `File > Open Folder` and choose this repository folder
3. Install recommended extensions (Python, GitHub Actions)
4. Activate your Python environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r automation/requirements.txt
   ```

## 🚀 GitHub Deployment

1. Push this folder to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Ronin Forensics Repo"
   git remote add origin https://github.com/yourusername/ronin-forensics
   git push -u origin main
   ```

2. Enable GitHub Pages or Actions if needed for automation.

## 📌 Notes

- You can extend this by integrating with MISP, PowerBI, or MITRE ATT&CK Navigator
- Use this with SpiderFoot, Crystal Blockchain, Chainalysis, or Maltego
