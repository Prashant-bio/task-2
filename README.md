# task-2
Phishing Email

## 🎯 Objective

Identify phishing characteristics in a suspicious email sample and create a detailed analysis report.

---

## 🛠️ Tools Required

* Email client or saved email file (text format)
* Online email header analyzers (e.g., [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx), [Google Messageheader](https://toolbox.googleapps.com/apps/messageheader/))
* URL scanning tools (e.g., VirusTotal, Sucuri)

---

## 📑 Deliverables

* A **report** listing all phishing indicators found in the suspicious email.

---

## 🔍 Steps / Mini Guide

1. **Obtain a sample phishing email** (safe samples available online).
2. **Check sender’s address** – Look for spoofing (e.g., `paypai.com` instead of `paypal.com`).
3. **Analyze email headers** – Verify SPF/DKIM/DMARC results and source IP location.
4. **Inspect links & attachments** – Hover over links to see actual URLs, check file types.
5. **Look for urgent or threatening language** (e.g., *“Immediate Action Required”*).
6. **Check for mismatched URLs** – Displayed vs actual link.
7. **Verify spelling & grammar** – Errors often indicate phishing.
8. **Summarize phishing traits** – Note all red flags found.

---

## 🧠 Key Concepts Covered

* **Phishing** – Fraudulent attempt to trick users into sharing credentials or sensitive data.
* **Email Spoofing** – Forging the “From” field to appear as a trusted sender.
* **Header Analysis** – Examining email metadata for authenticity.
* **Social Engineering** – Exploiting human psychology (fear, urgency, trust).
* **Threat Detection** – Identifying malicious links, domains, or attachments.

---

## ✅ Example Findings (Sample Report Snapshot)

* Sender domain spoofed: `support@paypai.com` (typo in domain).
* Header shows mismatch: Return-path from `randomserver.ru`.
* SPF/DKIM failed.
* Link redirects to `http://paypai-security-check.com/verify` (not PayPal, uses HTTP).
* Urgent wording: *“Your account will be suspended”*.
* Generic greeting: *“Dear Customer”*.
* Minor spelling errors detected.

**Conclusion:** Email is confirmed phishing. 🚨

**Action:** Do not click links or open attachments. Report immediately to IT/security team.
