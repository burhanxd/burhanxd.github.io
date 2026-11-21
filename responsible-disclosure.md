---
layout: page
title: Responsible Disclosure
nav_order: 2
---

Beyond bug bounty platforms, I've reported **50+ vulnerabilities** directly to companies through their responsible disclosure programs. These are organizations that may not have formal bug bounty programs on platforms like HackerOne or Intigriti, but still deserve to know when something is broken.

## Notable Disclosures

<div class="disclosure-item">
  <span class="disclosure-company">Google</span>
  <span class="disclosure-type disclosure-severity-high">IDOR</span>
  <p>Identified an Insecure Direct Object Reference vulnerability allowing unauthorized access to resources. Reported through Google's Vulnerability Reward Program.</p>
</div>

<div class="disclosure-item">
  <span class="disclosure-company">Yahoo</span>
  <span class="disclosure-type disclosure-severity-high">PII Disclosure</span>
  <span class="disclosure-type disclosure-severity-medium">XSS</span>
  <p>Discovered a PII disclosure vulnerability exposing sensitive user data, along with a Cross-Site Scripting (XSS) vulnerability. Reported through Yahoo's security team.</p>
</div>

<div class="disclosure-item">
  <span class="disclosure-company">Other Organizations</span>
  <span class="disclosure-type">Various</span>
  <p>Multiple additional findings across various companies, including access control bypasses, information disclosures, and injection vulnerabilities. All reported responsibly and remediated.</p>
</div>

## Vulnerability Types Found

| Type | Count |
|------|-------|
| Broken Access Control / IDOR | Multiple |
| Cross-Site Scripting (XSS) | Multiple |
| PII / Information Disclosure | Multiple |
| Business Logic Flaws | Multiple |
| API Security Issues | Multiple |

## My Disclosure Process

1. **Discover** — Identify the vulnerability during security research
2. **Document** — Create a detailed report with reproduction steps and impact assessment
3. **Report** — Reach out to the organization's security team through official channels
4. **Collaborate** — Work with the team to validate and remediate the issue
5. **Verify** — Confirm the fix is effective once deployed
