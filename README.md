# Hyeji Kim (Alex) — QA Portfolio

**🔗 [kimhj-alex.github.io/QA-Portfolio](https://kimhj-alex.github.io/QA-Portfolio)**

---

## About

This is the source repository for my QA portfolio — a collection of real findings from real use, documented in Jira-style bug reports and structured platform audits.

I'm a junior QA tester based in Seoul, Korea, working toward ISTQB CTFL certification (2026). My background is in design, writing, and building digital tools independently — which means I've spent years noticing the gaps between how things are supposed to work and how they actually do.

---

## What's Inside

```
QA-Portfolio/
├── index.html              # Homepage
├── audits.html             # Audits landing page
├── bug-reports.html        # Bug reports landing page
├── contact.html            # Contact page
├── resume.html             # Resume
├── audits/
│   ├── github-audit.html   # GitHub Usability Audit (4 findings)
│   └── istqb-audit.html    # ISTQB Website Audit (5 findings)
└── bug-reports/
    └── br-001 to br-014    # Individual bug report pages
```

---

## Audits

Two deep-dive platform audits form the centerpiece of this portfolio.

**Audit 01 — GitHub Usability Audit** · 4 findings  
Usability and discoverability issues found during active use of GitHub's web interface — hidden UI affordances, silent failure states, cross-browser regressions, and undocumented DNS setup gaps.

**Audit 02 — ISTQB Website Audit** · 5 findings  
Findings from the official ISTQB certification site — a search filter logic error that hides valid accredited providers, incomplete internationalization, an inaccessible accessibility widget, and a blank-loading quiz page.

---

## Bug Reports

14 individual findings across 9 platforms, documented in full Jira-style format.

| ID | Platform | Title | Severity |
|---|---|---|---|
| BR-001 | Instagram | Ad pricing information incomplete on mobile vs desktop | High |
| BR-002 | TikTok | Silent follow restriction on new accounts | Medium |
| BR-003 | Gmail | Undocumented desktop-only limitation for delegation | Medium |
| BR-004 | Squarespace / Gmail | Form email threading with hidden workaround | Low |
| BR-005 | Etsy | Missing category for wireless earbud cases | Low |
| BR-006 | Amazon KDP | Vague category conflict warning | Medium |
| BR-007 | YouTube Studio | Inconsistent music detection, no manual override | High |
| BR-008 | Google Calendar | No date jump navigation | Low |
| BR-009 | LinkedIn | Broken UI + date picker defaults to year 2160 on Brave | High |
| BR-010 | iPhone Clock Widget | Stale relative day label vs. app | Low |
| BR-011 | ISTQB Website | No obvious PDF download for glossary | Medium |
| BR-012 | Room Planner App | Known bugs in self-developed web app | Medium |
| BR-013 | Instagram | Invisible business account delegation feature | Medium |
| BR-014 | ISTQB Website | Accessibility widget unreachable via keyboard | High |

---

## Methodology

Every finding in this portfolio was discovered during actual use — not on practice bug-tracking sites or demo environments. The bugs here are the ones that interrupted real work: publishing patterns on Etsy, running ads for a small business, studying for a certification exam, building and deploying a web app.

Findings are documented with:
- Steps to reproduce
- Expected vs actual behavior
- Severity and priority assessment
- Suggested fix

Testing covered web, mobile (iOS), and cross-browser environments including Chrome, Brave, and Safari.

---

## Tech

Built with semantic HTML, CSS, and vanilla JavaScript. Hosted on GitHub Pages. No frameworks, no dependencies — just clean markup and an editorial design system built from scratch.

---

## Contact

**Email:** your@email.com  
**LinkedIn:** linkedin.com/in/yourhandle  
**Location:** Seoul, Korea (KST · UTC+9)  
**Available for:** Remote junior QA roles · Manual testing · Usability & accessibility testing
