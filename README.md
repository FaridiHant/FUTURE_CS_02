
# Phishing Email Detection & Awareness Report

## Cyber Security Internship | Future Interns 2026

---

## Overview

This project presents an analysis of a real phishing email sample, conducted as part of the Future Interns Cyber Security Internship 2026.

The analysis was strictly non-intrusive, focusing on identifying phishing indicators and creating awareness guidelines for businesses and employees.

---

## Scope

- **Target:** Phishing email impersonating Chase Bank (JPMorgan Chase)
- **Actual Sender:** merciayanmact@hotmail.com
- **Methodology:** Passive email header and content analysis

---

## Tools

- **Manual Header Analysis** —> Reviewed SPF, DKIM, DMARC authentication results
- **MXToolbox Email Header Analyzer** —> Verified routing and server information
- **Browser DevTools** —> Inspected embedded links and domains
- **EML Viewer** —> Viewed email as the victim would see it

---

## Key Findings

- Sender email does not match claimed identity —> **High Risk**
- Generic greeting with no real name used —> **High Risk**
- Fear and urgency tactics — account suspension threat —> **High Risk**
- Suspicious hidden link using URL shortener —> **High Risk**
- Mismatched email routing through personal accounts —> **Medium Risk**

---

## Email Classification

- **Status:** PHISHING
- **Overall Risk:** High
- **Total Indicators Found:** 4

---

## Repository Structure

- `README.md` — Project summary
- `Phishing_Detection_Report.pdf` — Detailed report
- `sample-5.eml` — Phishing email sample analyzed
- `screenshots/` — Supporting evidence

---

## Ethics & Compliance

- Used publicly available phishing samples for education only
- No real attacks or harmful actions performed
- Analysis conducted strictly for awareness and training purposes

---

## Internship Context

- **Program:** Future Interns Cyber Security Internship
- **Track:** Cyber Security (CS)
- **Task:** Phishing Email Detection & Awareness
- **Repository:** FUTURE_CS_02

---

**LinkedIn:** https://tz.linkedin.com/in/faridi-hant-60b06b344   
**Organization:** https://www.linkedin.com/company/future-interns/

---

> **Note:** This analysis was conducted in accordance with ethical security testing standards.
