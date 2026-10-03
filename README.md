# AML Level 1 Transaction Monitoring & Alert Investigation Case Study

## Executive Summary
This repository contains a simulated Level 1 Anti-Money Laundering (AML) transaction monitoring case study focusing on detecting suspicious patterns such as **Structuring (Smurfing)** and **Rapid Pass-Through Funds**.

---

## Case Overview
* **Case File ID:** AML-2026-TM-8891
* **Customer Name:** Apex Retail Solutions (Sole Proprietorship)
* **Expected Profile:** $15,000 – $20,000 / month
* **Alert Trigger:** Rapid movement of high-risk offshore funds & multiple cash outs below CTR reporting thresholds.

---

## Key Red Flags Identified
1. **Profile Mismatch:** Uncharacteristic inward wire transfer of $48,500 from Panama (High-Risk/Offshore Jurisdiction).
2. **Structuring (Smurfing):** 98% of the funds were withdrawn/transferred within 48 hours via 5 separate transactions ranging from $9,000 to $9,900 to evade the $10,000 Currency Transaction Report (CTR) threshold.
3. **Pass-Through / Layering:** Immediate movement of funds with no legitimate business rationale.

---

## Action Taken (L1 Analyst Decision)
* Conducted Customer Due Diligence (CDD) profile match.
* Flagged true positive suspicious activity.
* Drafted L1 Investigation Narrative and escalated case to L2 Compliance for potential SAR/STR filing and account restrictions.

---

## Repository Files
* `AML_Transaction_Data.csv` - Transaction ledger with red flag annotations.
