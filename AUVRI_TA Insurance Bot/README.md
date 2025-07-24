# 🤖 CTL10 – TA Insurance Automation

## 📌 Project Overview
The CTL10 TA Insurance Automation project streamlines the process of validating and managing TA (Technical Assistance) insurance coverage. The bot automatically checks TA insurance data, flags inconsistencies, and notifies responsible units for action. This ensures compliance and reduces manual effort.

## 🛠 Technologies Used
- **Automation Anywhere A360**
- **SharePoint**
- **Outlook (Email Trigger)**
- **Excel (Data Processing)**

## 🔁 Automation Flow
1. **Trigger:** Bot is triggered on schedule or via email
2. **Data Collection:** Retrieve TA insurance records from SharePoint
3. **Validation:** Cross-check entries for missing/invalid information
4. **Notification:** Send summary to CTL focal and responsible RM
5. **Logging:** Save run details and validation report to shared drive

## ✅ Key Benefits
- Saves significant processing time (previously manual and repetitive)
- Ensures data integrity and accuracy in TA insurance records
- Operates with minimal human intervention
- Provides early detection of errors to prevent downstream issues

## 📅 Bot Schedule
- **Run Time:** 3:00 AM – 9:30 PM (Non-24/7)
- **Frequency:** Every 30 minutes
- **Retries:** Enhanced retry mechanism for SharePoint/API issues

## 📈 Improvements Made
- Implemented logging and exception capture
- Added conditional notifications based on type of issue
- Fine-tuned SharePoint integration with added resilience

## 🔒 Data Handling
- No personal identifiable information (PII) is stored
- Logs are retained for audit trail only (masking applied where needed)

---

### 📁 `/images/`
*(You can include the following images here:)*

- `process-flow.png` – A diagram of the flow above
- `sample-email.png` – Sample of automated email output (with redacted content)
- `sharepoint-input.png` – Input sample file from SharePoint

---

### ✅ `summary.md`

```markdown
## CTL10 TA Insurance – Summary

**Business Problem:**
Manual validation of TA insurance coverage was error-prone and time-consuming, often delayed due to reliance on manual review processes.

**Automation Objective:**
Automate the end-to-end process to ensure faster turnaround, data accuracy, and timely notifications to stakeholders.

**Stakeholders:**
- CTFA-AE (AP)
- Responsible RMs from Sector Groups
- Controllers Department (CTL)

**Result:**
- Reduced processing time by 80%
- Early detection of insurance mismatches
- Positive feedback from CTL focal on improved turnaround

**Next Steps:**
- Monitor stability over the next quarter
- Evaluate integration with ServiceNow for ticket creation
