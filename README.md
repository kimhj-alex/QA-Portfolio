# Hyeji Kim (Alex) — QA Portfolio: Manual Testing & Gen AI

**🔗 [kimhj-alex.github.io/QA-Portfolio](https://kimhj-alex.github.io/QA-Portfolio)**

---

## About

This is the source repository for my QA portfolio — a collection of real findings from real use, documented in Jira-style bug reports, structured platform audits, and narrative Gen AI case studies.

I'm a junior QA tester based in Seoul, Korea, ISTQB CTFL certified (2026), working toward CT-GenAI next. My background is in design, writing, and building digital tools independently — which means I've spent years noticing the gaps between how things are supposed to work and how they actually do. Over the past year, that same habit turned into hands-on Gen AI evaluation: catching where AI-assisted work sounded right but wasn't, across code, creative writing, and business planning.

---

## What's Inside

```
QA-Portfolio/
├── index.html                        # Homepage
├── audits.html                       # Audits landing page
├── bug-reports.html                  # Bug reports landing page
├── gen-ai-cases.html                 # Gen AI case studies landing page
├── contact.html                      # Contact page
├── resume.html                       # Resume
├── audits/
│   ├── github-audit.html             # GitHub Usability Audit (4 findings)
│   ├── istqb-audit.html              # ISTQB Website Audit (5 findings)
│   └── shoebox-planner-audit.html    # Shoebox Planner Self-Audit (7 findings)
├── bug-reports/
│   ├── instagram-ads-fees.html       # BR-001 · Instagram
│   ├── tiktok-follow.html            # BR-002 · TikTok
│   ├── gmail-delegation.html         # BR-003 · Gmail
│   ├── squarespace-threading.html    # BR-004 · Squarespace / Gmail
│   ├── etsy-category.html            # BR-005 · Etsy
│   ├── kdp-category.html             # BR-006 · Amazon KDP
│   ├── youtube-music.html            # BR-007 · YouTube Studio
│   └── google-calendar.html          # BR-008 · Google Calendar
└── gen-ai/
    ├── app-development.html          # Case 01 · The Ellipse Math Shortcut
    ├── creative-writing.html         # Case 02 · Consistency Across Books
    └── business-planning.html        # Case 03 · Confidence vs. Correctness
```

---

## Audits

Three structured platform audits form the centerpiece of the manual testing side of this portfolio.

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

## Gen AI Cases

Three narrative case studies — not structured audits, but retrospectives on real AI-assisted projects, examining the specific moments where the output sounded right and wasn't. Every finding is verified against something outside the conversation itself: shipped code, a published book, or a live site.

**Case 01 — The Ellipse Math Shortcut** · App Development  
An AI coding assistant recommended faking a fix instead of doing real ellipse-collision math for a room-planner app, and only produced the correct math once asked directly. A rotation-gated shortcut kept recurring across multiple fix attempts, isolated through systematic black-box testing rather than code review.

**Case 02 — Consistency Across Books** · Creative Writing  
Co-writing two published romantic fantasy novellas surfaced quiet context drift (an inverted age gap between two books' characters, a scene's logic surviving its own correction, sensory detail bleeding from one scene into another) and, at its most serious, a misattributed manuscript that led to an invented scene with no source at all.

**Case 03 — Confidence vs. Correctness** · Business Planning  
Building pricing and policies for a real tattoo-translation service surfaced four moments where AI output sounded finished but wasn't: a settled decision regenerated from scratch, reassurance standing in for a direct answer, flawless arithmetic run on the wrong rate card, and a draft instruction shipped among otherwise-finished client copy.

---

## Methodology

Every finding in this portfolio was discovered during actual use — not on practice bug-tracking sites, demo environments, or adversarial "red-team" prompts designed to break something. The bugs and Gen AI findings here are the ones that interrupted real work: publishing on Etsy, running ads for a small business, studying for a certification exam, building and deploying a web app, writing and publishing novellas, planning a real service.

Audit and bug report findings are documented with:
- Steps to reproduce
- Expected vs actual behavior
- Severity and priority assessment
- Suggested fix

Gen AI case studies are documented with:
- The specific exchange where the output looked right and wasn't
- What actually happened underneath
- Verification against something checkable outside the conversation

Testing covered web, mobile (iOS), iPad, and cross-browser environments including Chrome, Brave, and Safari. The Shoebox Planner audit used checklist testing, exploratory testing, and cross-device regression testing across desktop and iPad.

---

## Tech

Built with semantic HTML, CSS, and vanilla JavaScript. Hosted on GitHub Pages. No frameworks, no dependencies — just clean markup and an editorial design system built from scratch.

---

## Contact

**Email:** kimhj.business@gmail.com  
**LinkedIn:** linkedin.com/in/alexhyejikim  
**Location:** Seoul, Korea (KST · UTC+9)  
**Available for:** Remote junior QA roles · Manual testing · Usability & accessibility testing · Gen AI evaluation
