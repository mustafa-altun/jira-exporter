# JIRA Excel Exporter (+ Attachments Downloader)

This script extracts **JIRA issues**, including **comments, worklogs, descriptions, and attachments**, and exports them into an **Excel file**.  
Additionally, it **downloads attachments** from JIRA and saves them locally.  

📌 **Features:**
- Extracts **Summary, Descriptions, Comments, Status, Worklogs, Created Date, Updated Date and Attachments** from JIRA.
- Exports **Descriptions, Comments, Worklogs, and Attachments** into separate sheets.
- It downloads all **attachments** but calculates the total disk requirement before starting the download and waits for feedback from the user whether to continue the process or not. You can also continue without downloading the attachments.
- **Supports multi-line descriptions and comments** (Newline characters are preserved in Excel).

---

## 📥 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/jira-exporter.git
   cd jira-exporter
