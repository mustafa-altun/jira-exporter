# JIRA Issue Exporter (Excel + Attachments Downloader)

This script extracts **JIRA issues**, including **comments, worklogs, descriptions, and attachments**, and exports them into an **Excel file**.  
Additionally, it **downloads attachments** from JIRA and saves them locally.  

📌 **Features:**
- Extracts **Summary, Status, Created Date, Updated Date** from JIRA.
- Saves **Descriptions in a separate Excel sheet**.
- Exports **Comments, Worklogs, and Attachments** into separate sheets.
- Downloads all **attachments** and calculates total disk space required.
- **Interactive mode**: Asks whether to download attachments.
- **Supports multi-line descriptions** (Newline characters are preserved in Excel).

---

## 📥 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/jira-exporter.git
   cd jira-exporter
