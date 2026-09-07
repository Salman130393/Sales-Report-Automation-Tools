# Sales Report Automation Tools

A collection of VBA and Google Apps Script tools built to automate 
manager-wise sales report generation and email distribution for a field 
sales team of 500+ users.

## 📌 Overview
This project automates two key processes:
1. Splitting a master report into individual files based on RSM/ASM hierarchy
2. Automatically emailing the right report to the right manager with proper CC routing

## 🛠️ Tools Used
- Excel VBA (Macros)
- Google Apps Script (JavaScript)
- Gmail API (via Apps Script)
- Google Drive API (via Apps Script)

## 📂 Contents

### 1. RSM/ASM Report Splitter (VBA)
Scans a master workbook, identifies unique RSM/ASM names, and generates 
individual filtered Excel files for each — eliminating manual filtering 
and copy-pasting.

### 2. Automated Email Distribution (Google Apps Script)
Reads a report folder, matches each report file to the correct recipient 
using an employee master sheet, applies hierarchy-based CC logic 
(Manager → their reporting boss → Head Office), and sends emails 
automatically via Gmail.

## 💡 Skills Demonstrated
- VBA Macro Programming (Dictionary objects, AutoFilter automation, 
  dynamic file handling)
- Google Apps Script (Spreadsheet & Drive API integration)
- Process Automation & Workflow Design
- Email Automation Logic (dynamic CC/recipient routing)

## 🚀 Impact
Eliminated a fully manual report-splitting and distribution process, 
saving significant time each reporting cycle and removing human error 
from manager-wise report delivery.

