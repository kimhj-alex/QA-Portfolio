# Hyeji Kim (Alex) — QA Portfolio

**🔗 [kimhj-alex.github.io/QA-Portfolio](https://kimhj-alex.github.io/QA-Portfolio)**

---

## About

This is the source repository for my QA portfolio — a collection of real findings from real use, documented in Jira-style bug reports and structured platform audits.

I'm a junior QA tester based in Seoul, Korea, ISTQB CTFL certified (2026). My background is in design, writing, and building digital tools independently — which means I've spent years noticing the gaps between how things are supposed to work and how they actually do. My background in design, writing, and building digital tools means I notice gaps that purely technical testers sometimes miss.

---

## What's Inside

```
QA-Portfolio/
├── index.html                        # Homepage
├── audits.html                       # Audits landing page
├── bug-reports.html                  # Bug reports landing page
├── contact.html                      # Contact page
├── resume.html                       # Resume
├── audits/
│   ├── github-audit.html             # GitHub Usability Audit (4 findings)
│   ├── istqb-audit.html              # ISTQB Website Audit (5 findings)
│   └── shoebox-planner-audit.html    # Shoebox Planner Self-Audit (7 findings)
└── bug-reports/
    ├── instagram-ads-fees.html       # BR-001 · Instagram
    ├── tiktok-follow.html            # BR-002 · TikTok
    ├── gmail-delegation.html         # BR-003 · Gmail
    ├── squarespace-threading.html    # BR-004 · Squarespace / Gmail
    ├── etsy-category.html            # BR-005 · Etsy
    ├── kdp-category.html             # BR-006 · Amazon KDP
    ├── youtube-music.html            # BR-007 · YouTube Studio
    └── google-calendar.html          # BR-008 · Google Calendar
```

---

## Audits

Three structured platform audits form the centerpiece of this portfolio.

**Audit 01 — GitHub Usability Audit** · 4 findings  
Usability and discoverability issues found during active use of GitHub's web interface — hidden UI affordances, silent failure states, cross-browser regressions, and undocumented DNS setup gaps.

**Audit 02 — ISTQB Website Audit** · 5 findings  
Findings from the official ISTQB certification site — a search filter logic error that hides valid accredited providers, incomplete internationalization, an inaccessible accessibility widget, and a blank-loading quiz page.

**Audit 03 — Shoebox Planner Self-Audit** · 7 findings  
A structured self-audit of a web app I built from scratch, tested across desktop and iPad using checklist, exploratory, and cross-device regression testing. Bugs found across undo/redo logic, save/load functionality, and touch-specific regressions.

---

## Bug Reports

8 individual findings across 8 platforms, documented in full Jira-style format.

| ID | Platform | Title | Severity |
|---|---|---|---|
| BR-001 | Instagram | Ad pricing information incomplete on mobile vs desktop | High |
| BR-002 | TikTok | Silent follow restriction on new accounts with false UI feedback | Medium |
| BR-003 | Gmail | Account delegation feature absent from mobile app with no guidance | Medium |
| BR-004 | Squarespace / Gmail | Form submissions thread into single Gmail conversation | Low |
| BR-005 | Etsy | No category exists for wireless earbud cases — sellers forced to misclassify | Low |
| BR-006 | Amazon KDP | Category conflict warning provides no explanation or actionable guidance | Medium |
| BR-007 | YouTube Studio | Music content detection inconsistent with no manual override | High |
| BR-008 | Google Calendar | No date jump navigation + mobile search limited to two-year window | Low |

---

## Methodology

Every finding in this portfolio was discovered during actual use — not on practice bug-tracking sites or demo environments. The bugs here are the ones that interrupted real work: publishing on Etsy, running ads for a small business, studying for a certification exam, building and deploying a web app.

Findings are documented with:
- Steps to reproduce
- Expected vs actual behavior
- Severity and priority assessment
- Suggested fix

Testing covered web, mobile (iOS), iPad, and cross-browser environments including Chrome, Brave, and Safari. The Shoebox Planner audit used checklist testing, exploratory testing, and cross-device regression testing across desktop and iPad.

---

## Tech

Built with semantic HTML, CSS, and vanilla JavaScript. Hosted on GitHub Pages. No frameworks, no dependencies — just clean markup and an editorial design system built from scratch.

---

## Contact

**Email:** your@email.com  
**LinkedIn:** linkedin.com/in/yourhandle  
**Location:** Seoul, Korea (KST · UTC+9)  
**Available for:** Remote junior QA roles · Manual testing · Usability & accessibility testing
