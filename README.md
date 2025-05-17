# Email-Automation
# 📧 Cold Email Automation Using Python & Gmail SMTP

This project automates the process of sending personalized cold emails using Python and Gmail’s SMTP service.  
It reads contact information from an Excel sheet and sends a customized email to each recipient based on their name and company.

## 🚀 Features

- ✅ Reads contact info from an Excel or CSV file  
- ✅ Sends personalized cold emails to each contact  
- ✅ Uses Gmail SMTP with secure authentication  
- ✅ Logs email status in the terminal  
- ✅ Simple structure – all files in one folder  

## 🛠️ Prerequisites

- Python 3.x installed
- A Gmail account with **App Password** enabled (if 2FA is on)

### 📦 Required Python Libraries

Install the required libraries using pip:

```bash
pip install pandas openpyxl

```

## 📁 Files Used

All files should be in the same folder:
```
.
├── contacts.xlsx # Your contact data
├── email_script.py # The email automation script
└── README.md # This documentation
```


## 📋 contacts.xlsx Format

Ensure your spreadsheet has the following columns:

| First Name	 |  Company Name	  | mailid |
|:-----|:--------:|------:|
| John   | OpenAI | john@example.com |
| Sarah   |  DataCorp  |   	sarah@example.org |
