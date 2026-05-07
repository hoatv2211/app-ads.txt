---
name: Privacy Policy Intake Form
description: "Use to quickly fill game details and auto-generate a Google Play privacy policy in English with HTML output."
argument-hint: "Fill the form fields and run"
agent: "chplay-privacy-writer"
---
Generate a Google Play privacy policy using the form below.

Rules:
- Final output language must be English.
- Return both Markdown policy and a full responsive HTML page.
- Do not assume unknown legal/data facts; use [TO_CONFIRM: ...] placeholders.
- If developer name/email are missing, use MADONE Studio and madonestudiogame@gmail.com.

Intake Form
- App name:
- Package name (Android):
- Developer/Company name (default: MADONE Studio):
- Contact email (default: madonestudiogame@gmail.com):
- Website URL (optional):
- Effective date:
- Last updated date:
- Target audience: General / 13+ / Kids
- Regions served (optional):

Data Collection
- Personal data collected (if any):
- Device/app data collected (if any):
- Approximate location collected: Yes/No
- Precise location collected: Yes/No
- User-generated content collected: Yes/No

Third-Party Services
- Ads SDKs (AdMob, AppLovin, Unity Ads, etc.):
- Analytics SDKs (Firebase Analytics, etc.):
- Crash reporting (Firebase Crashlytics, etc.):
- Authentication providers (Google, Facebook, etc.):
- Payment providers (Google Play Billing, etc.):

Data Handling
- Why data is used:
- Data sharing categories:
- Data retention period:
- Security measures (high-level):
- User rights request method:
- Deletion request method:

Children and Compliance
- Directed to children under 13: Yes/No
- COPPA/GDPR-K handling notes:

Output required:
1. Known vs Missing table
2. Final privacy policy in Markdown (English)
3. Final privacy policy as responsive HTML (single file)
4. Google Play readiness checklist
