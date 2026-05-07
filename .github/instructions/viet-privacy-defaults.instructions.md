---
name: Viet Privacy Defaults
description: "Use when the user says viet privacy, write privacy, CH Play privacy, Google Play privacy, app privacy policy, or game privacy policy. Apply MADONE Studio defaults and output format."
---
# Privacy Writing Defaults For This Workspace

Apply these defaults whenever the user asks to write a privacy policy (especially with trigger phrase: viet privacy).

Default company profile
- Developer/Company: MADONE Studio
- Contact email: madonestudiogame@gmail.com

Output requirements
- Policy language: English
- Always provide both outputs:
  - Markdown privacy policy
  - Full responsive HTML page (single file with embedded CSS)
- Use MADONE brand HTML template at .github/templates/madone-privacy-template.html as the base for every privacy page.
- Default logo placeholders:
  - {{BRAND_LOGO_URL}}: ./assets/madone-logo.png
  - {{BRAND_LOGO_ALT}}: MADONE Studio logo
- If any legal/data detail is missing, do not guess. Use placeholders in format: [TO_CONFIRM: ...]

Policy structure baseline
- Introduction and scope
- Information collected
- How information is used
- Sharing with third parties
- Data retention
- Security
- Children's privacy
- User rights and choices
- Contact information
- Changes to this policy

Quality rules
- Keep legal wording clear and practical for Google Play review context.
- Do not include unrelated legal agreements unless explicitly requested.
- Preserve factual accuracy over stylistic variation.
