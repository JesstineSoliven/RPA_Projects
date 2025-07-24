# 🤖 CTL10 – TA Insurance Premium Automation

## 📌 Project Overview
The CTL10 RPA project automates the processing of insurance premiums for TA Consultants and Resource Persons. It addresses key challenges such as inconsistent timing, manual effort, and delayed payments by streamlining the end-to-end workflow—from data extraction to journal voucher creation. The bot ensures timely and accurate recording of insurance premiums, improving operational efficiency and compliance.

## 🛠 Technologies Used
- **Automation Anywhere A360**
- **SharePoint (TADL)**
- **IDS & CMS Systems**
- **Excel (EWF Generation & Computation)**
- **Outlook (Notifications)**
- **RPA Database (Contract Tracking)**

## 🔁 Automation Flow
1. **Trigger:** Bot runs daily during the 3rd week of each month until all transactions are processed.
2. **Participant Bot:**
   - Extracts contract data from IDS and CMS.
   - Prepares input files for processing.
3. **Consumer Bot:**
   - Processes transactions from 6:00 AM to 9:30 PM.
   - Generates EWF, PD logs, and journal vouchers.
   - Uploads outputs to SharePoint and updates RPA DB.
4. **Notification:** Sends automated emails for successful runs and exceptions.
5. **Logging:** Maintains audit trail and summary reports.

## ✅ Key Benefits
- **Time Savings:** Average processing time reduced to 4 minutes (simple) and 20 minutes (complex).
- **Accuracy:** Standardized EWF computation and reduced manual errors.
- **Scalability:** Supports parallel processing across machines.
- **Timeliness:** Insurance recording now triggered at contract start or revised termination, not just disbursement or closing.
- **Centralized Data:** All outputs and logs stored in RPA DB and SharePoint.

## 📅 Bot Schedule
- **Run Period:** 3rd week of each month
- **Daily Run Time:** 6:00 AM – 9:30 PM
- **Frequency:** Daily until all transactions are consumed
- **Volume:** ~826 transactions/month (Feb–Apr 2025)

## 📈 Performance Highlights
- **Feb–Apr 2025:** 2,479 transactions processed
- **Processing Time Saved:** ~99 hours/month
- **Improved Turnaround:** Faster and more consistent premium recording
- **Positive Feedback:** CTLA-TA team reports improved client service and reduced backlog

## 🔒 Data Handling
- No personal identifiable information (PII) is stored
- Logs retained for audit purposes with masking applied

---

### 📁 `/images/`
Include the following visual assets:
- `process-flow.png` – Diagram of Participant and Consumer Bot workflow
- `sample-email.png` – Example of automated notification
- `sharepoint-input.png` – Sample input/output files

---

### ✅ `summary.md`

```markdown
## CTL10 TA Insurance – Summary

**Business Problem:**
Manual processing of TA insurance premiums led to delays, inconsistent timing, and increased effort, especially during high-volume periods.

**Automation Objective:**
Automate the extraction, validation, and recording of insurance premiums to ensure timely, accurate, and scalable processing.

**Stakeholders:**
- CTLA-TA Processors
- Sector Group RMs
- Controllers Department (CTL)

**Results:**
- 80% reduction in processing time
- Increased transaction volume handled without additional resources
- Enhanced data accuracy and auditability

**Next Steps:**
- Monitor bot performance and stability
- Explore integration with ServiceNow for ticketing
- Expand scope to include additional contract scenarios
```

---
