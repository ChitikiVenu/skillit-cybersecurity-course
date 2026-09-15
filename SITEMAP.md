# Sitemap — /courses/Cybersecurity/

```
/courses/Cybersecurity/
│
├── index.html                                              → Course Overview (landing page)
│
├── module-1-cybersecurity-foundations/
│   └── index.html                                          → Module 1 — Cybersecurity & Ethical Hacking Foundations (2 Weeks / 20 Hrs)
│
├── module-2-reconnaissance-scanning-enumeration/
│   └── index.html                                          → Module 2 — Reconnaissance, Scanning & Enumeration (3 Weeks / 30 Hrs)
│
├── module-3-system-hacking-malware-social-engineering/
│   └── index.html                                          → Module 3 — System Hacking, Malware & Social Engineering (3 Weeks / 30 Hrs)
│
├── module-4-penetration-testing-web-exploitation/
│   └── index.html                                          → Module 4 — Penetration Testing & Web Exploitation (6 Weeks / 60 Hrs)
│
├── module-5-advanced-exploitation-cryptography-mobile-security/
│   └── index.html                                          → Module 5 — Advanced Exploitation, Cryptography & Mobile Security (2 Weeks / 20 Hrs)
│
├── module-6-security-operations-cyber-defense/
│   └── index.html                                          → Module 6 — Security Operations & Cyber Defense (2 Weeks / 20 Hrs)
│
└── assets/
    └── css/
        └── style.css                                       → Shared site stylesheet (dark, enterprise cybersecurity theme)
```

## Live URL structure (once deployed at skilliteducation.com)

| Page | URL |
|---|---|
| Course Overview | `skilliteducation.com/courses/Cybersecurity/` |
| Module 1 | `skilliteducation.com/courses/Cybersecurity/module-1-cybersecurity-foundations/` |
| Module 2 | `skilliteducation.com/courses/Cybersecurity/module-2-reconnaissance-scanning-enumeration/` |
| Module 3 | `skilliteducation.com/courses/Cybersecurity/module-3-system-hacking-malware-social-engineering/` |
| Module 4 | `skilliteducation.com/courses/Cybersecurity/module-4-penetration-testing-web-exploitation/` |
| Module 5 | `skilliteducation.com/courses/Cybersecurity/module-5-advanced-exploitation-cryptography-mobile-security/` |
| Module 6 | `skilliteducation.com/courses/Cybersecurity/module-6-security-operations-cyber-defense/` |

A machine-readable `sitemap.xml` is included at the zip root for search-engine submission — update the domain there if the final live path differs.

## Page structure (applies to every module page)

1. **H1** — Module title + timeframe, e.g. *"Module 1 — Cybersecurity & Ethical Hacking Foundations (2 Weeks)"*
2. **Overview (hero)** — outcome-focused intro, who it's for, real-world relevance
3. **What You Will Learn** — 11–13 detailed, industry-aligned bullet points
4. **Tools You Will Use** — tool cards with a logo-placeholder slot (`aria-label="LOGO: <ToolName>"`, ready to swap for real logo images/SVGs) and a one-line explanation
5. **Hands-On Labs** — 5 enterprise/SOC/pentest-style lab scenarios
6. **Assessment** — knowledge assessment + practical evaluation
7. **Projects** — 3 portfolio-grade project briefs
8. **Outcome** — module outcome statement + mapped job roles

## Notes for whoever deploys this

- Drop real tool logo SVGs/PNGs into `assets/img/tools/` and replace the `.tool-logo` placeholder `<div>` in each page with an `<img>` — the `aria-label`/`title` on every placeholder already carries the `[LOGO: ToolName]` marker so they're easy to find and swap.
- All "Enroll Now" / "Talk to Advisor" buttons point to `#enroll`, which anchors to the footer. Wire these to your actual enrollment form/CRM before going live.
- Salary figures on the overview page are broad, non-exaggerated indicative ranges — update with your placement-team's current data before publishing.
- No AI branding or AI-tool references appear anywhere on the site, per brief — Module 6 was reframed from the source brochure's "AI-Powered Cyber Defence" into a traditional SOC/Blue-Team "Security Operations & Cyber Defense" module.
