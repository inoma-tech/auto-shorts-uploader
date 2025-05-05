---
title: Privacy Policy
last_updated: 2025-05-06
---

# Privacy Policy
_Last updated: 2025-05-06_

**AutoShortsUploader** (“**Service**”, “we”) respects your privacy.
This policy explains what data we collect, why we collect it, and how we safeguard it.

---

## 1. Data We Collect

| Category | Examples | Purpose |
|----------|----------|---------|
| **OAuth Credentials** | Access & refresh tokens, TikTok user ID, YouTube channel ID | Authenticate API calls; post videos to your accounts |
| **Video Metadata** | Title, tags, visibility flag, upload timestamp | Required to publish content and show status in dashboard |
| **Operational Logs** | Success/ error codes, time-stamps | Debugging and rate-limit management |

> **We do not collect** personal profile details such as email, phone number, or biometric identifiers.

---

## 2. How We Use Data
* Authenticate and post videos you instruct us to upload.
* Display upload status/analytics in the dashboard.
* Monitor errors and API-rate limits to maintain uptime.
* **We never sell or share your data** with third parties for advertising purposes.

---

## 3. Storage & Security
* Data is stored in an encrypted PostgreSQL database hosted on **AWS Tokyo (ap-northeast-1)**.
* Network access is restricted by VPC firewall; credentials are encrypted at rest.
* Only the account owner can access the database via role-based IAM.

---

## 4. Data Retention
| Data type | Retention period |
|-----------|-----------------|
| OAuth tokens | Stored until you revoke authorization or 90 days of inactivity |
| Video metadata & logs | 30 days after upload, then automatically purged |

---

## 5. Your Rights
You may request to view or delete your stored data at any time by emailing **admin@inoma.tech**. We will comply within **72 hours**.

---

## 6. Children’s Privacy
The Service is not intended for children under 13, and we do not knowingly collect their data.

---

## 7. Changes to This Policy
We may update this Policy periodically. Updates will be posted here with a new “last updated” date. Continued use of the Service after changes constitutes acceptance.

---

## 8. Contact
For privacy inquiries, reach us at **admin@inoma.tech**.
