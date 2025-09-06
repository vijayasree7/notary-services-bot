# Notary Services Bot – Automation Anywhere A360 (Community Edition) – BotsDNA

## 📌 Overview
The **Notary Services** Bot is built to automate the process of filling Notary Advocate details using **Automation Anywhere A360 (Community Edition)**.
It reads advocate information from an Excel file, navigates to the notary services webpage, fills in the form fields (Advocate Name, Area of Practice, District), and logs the execution details.

---

## ⚙️ Bot Logic
1. **Start**
2. **Log File Creation** → Creates a log file to capture bot execution details
3. **Read Excel Data** → Reads Advocate details (Name, Area, District)
4. **Open Browser** → Launches browser and navigates to the Notary Services site
5. **Form Filling** → Inputs advocate details into the webpage form
6. **Submit Details** → Confirms submission for each record
7. **Bot Execution** → Iterates through all Excel records and logs results
8. **End**

---

## 🖼️ Screenshot

Workflow:  
![Notary_Services Workflow](notary-services-workflow.png)
Example:  
![Notary_Services Log](notary-services-log.png)

---

## 🔄 How to Recreate This Bot

1. Log in to **Automation Anywhere A360 (Community Edition)**.
2. Create a new Project / Bot.
3. Import NotaryServices_Main.json (for A360).
4. Place the input file AP-ADVOCATES.xlsx in the correct path (or update the file path inside the bot).
5. Run the bot → check the generated execution.log and form submission results.

## 🗂️ Repository Structure
notary-services-bot/

|- README.md

|- NotaryServices_Bot.json                         # Bot definition

|- AP-ADVOCATES.xlsx                               # Sample Excel input file

|- NotaryServices_LogFile.txt                      # Sample log file

|- notary_services_workflow.png                    # Workflow screenshot

|- notary_services_log.png                         # Output screenshot


## 📖 Metadata

- **Author:** Vijaya Sree Janjanam
- **Created:** 06-Sep-2025
- **Bot Type:** UiPath / Automation Anywhere A360
- **Domain:** Legal Automation (Notary Services)

---

![Automation Anywhere](https://img.shields.io/badge/Automation%20Anywhere-A360-orange)
![Bot Type](https://img.shields.io/badge/Notary%20Services%20Bot-blue)

---

## 🚀 Next Steps
-  Visit my next repositories for other bot automation solutions.

--- 
