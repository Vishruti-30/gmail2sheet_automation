# 📧 Automate Gmail to Google Sheets Logging with Zapier

A simple automation workflow that extracts details from incoming Gmail emails and logs them into a Google Sheet for easy tracking and analysis.

---

## 📁 Tools Used
- **Zapier** (automation platform)  
- **Gmail** (email source)  
- **Google Sheets** (data storage)

---

## 🎯 Project Objectives
- Automatically capture incoming email details  
- Extract key fields: sender name, sender email, subject, date  
- Log data in a structured Google Sheet  
- Enable easy email record-keeping and analysis  

---

## ✅ Steps Performed

1. **Set Up Google Sheet**  
   - Created a sheet named `EmailLog`  
   - Added headers: Name, Email, Subject, Date

2. **Create Zap in Zapier**  
   - Configured Gmail trigger: New Email Matching Search  
   - Filtered emails by search criteria (e.g. specific sender)

3. **Connect Google Sheets Action**  
   - Mapped Gmail email details to corresponding columns  
   - Enabled creation of new rows per incoming email

4. **Test & Deploy**  
   - Tested Zap with sample emails  
   - Enabled Zap for continuous automation

---

## ⚙️ Configuration Details
- Gmail Search String Example: `from:(example@gmail.com)`  
- Google Sheets Spreadsheet: `EmailLog`  
- Mapped Fields:  
  - Name → Sender’s Name  
  - Email → Sender’s Email  
  - Subject → Email Subject  
  - Date → Email Received Date

---

## 🚀 Next Steps
- Expand parsing to include email body content  
- Add multi-condition filters for advanced email selection  
- Integrate with other tools like Slack or CRM platforms  
- Automate notifications on new entries  

---

## 📂 Folder Structure
```
├── Email Log.xlsx # Sample output Excel sheet with logged email data
├── zap_flow_diagram.png # Visual flowchart of the Zap automation steps
└── README.md # This project documentation file
```
