---
layout: post
title:  "Using Excel Scripts and Power Automate to Convert CSV to XLSX"
---
# {title}
### Instructions
1.  Build Sample Data - CSV - Modify existing data
    1.  Create SP Site
    1.  Save CSV to Site
1.  Create Template
    1.  Create Excel Template File (in SP)
    1.  Copy Excel Script to DEV
    1.  Test Script
1.  PowerAutomate - Create Flow
    1.  Read Text File
    1.  Duplicate Template
    1.  Pass Text String into Script
    1.  
1.  Code
    1.  Modifications to account for end of line
    1.  Credit Sources
##  Scenario #1 Part 1
Your ERP Report Output generates a CSV easily but you want to mass distribute it.  A CSV for some is no big deal, but for most, ease of use is number one, so they'd prefer it to be formatted upon receipt.
## Scenario #1 Part 2
Taking it a step further, the user wants a clean format, but they also want the new workbook filtered and separated into individual tabs.
## Scenario #2
Your ERP Report Output generates a CSV of data which you need to loop over withing PowerAutomate.  The user wants a notification sent for each item in the CSV and they want it tracked within the new workbook (added column).