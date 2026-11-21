# Workora Pharmacovigilance Internship — Emmanuel Ademola

**Intern:** Emmanuel Ademola (WKR-NOV26TODEC26-1589)  
**Institution:** Adekunle Ajasin University, Akungba-Akoko, Ondo State  
**Role:** Pharmacovigilance Intern (Remote, 1 Month)  
**Period:** 20 November 2026 → 20 December 2026  
**Platform:** Workora Labs (Workora.in)  
**Repo purpose:** Evidence portfolio for all 8 Workora milestones — one folder per task, each with a signed PDF submission.

> All cases in this portfolio are **fictional/synthetic training data** from Workora packs, for educational analysis only. No real patient data.

---

## 📁 Repo Structure (single repo, grouped by task)

```
workora-pharmacovigilance-internship/
├── README.md                  ← you are here
├── assets/
│   ├── signature.png          ← cleaned handwritten signature (transparent PNG, background removed)
│   ├── signature_original_color.png
│   └── offer_letter.jpg       ← Workora offer letter (20/11/2026)
├── Task01_LinkedIn_Onboarding/
├── Task02_ADR_Identification/          ✅ PDF submitted-ready
├── Task03_ADR_Reporting/
├── Task04_Causality_Assessment/
├── Task05_Severity_Classification/
├── Task06_ICSR/
├── Task07_Risk_Management_Plan/
├── Task08_PSMF_Summary/
├── calendar_reminders.ics     ← import to Google Calendar for daily reminders
└── TASK_TRACKER.md            ← 30-day plan, one task focus per day
```

**Why one repo, not 8 separate repos?** Employers and Workora reviewers can see the full journey in one place, GitHub contribution calendar shows daily work, and each task folder stays self-contained with its PDF + source pack. If you prefer 8 separate repos later, each folder can be split out in 1 minute.

---

## ✅ Task Tracker

| # | Task | Folder | Status | Target Date |
|---|------|--------|--------|-------------|
| 1 | Platform Onboarding & Offer Letter Acceptance (LinkedIn post) | Task01_LinkedIn_Onboarding | ⬜ Pending | 21 Nov 2026 |
| 2 | ADR Identification Basics | Task02_ADR_Identification | ✅ PDF ready (signed) | 22 Nov 2026 |
| 3 | ADR Reporting & Documentation | Task03_ADR_Reporting | ⬜ Pending | 24 Nov 2026 |
| 4 | Causality Assessment (Naranjo / WHO-UMC) | Task04_Causality_Assessment | ⬜ Pending | 26 Nov 2026 |
| 5 | Severity & Case Classification (ICH E2A) | Task05_Severity_Classification | ⬜ Pending | 28 Nov 2026 |
| 6 | Individual Case Safety Report (ICSR + MedDRA) | Task06_ICSR | ⬜ Pending | 02 Dec 2026 |
| 7 | Risk Management Plan (RMP) | Task07_Risk_Management_Plan | ⬜ Pending | 08 Dec 2026 |
| 8 | Final PSMF Summary | Task08_PSMF_Summary | ⬜ Pending | 15 Dec 2026 |
| — | Buffer / review / submit all on Workora | — | ⬜ | 16–20 Dec 2026 |

Full day-by-day plan: see [TASK_TRACKER.md](TASK_TRACKER.md). Calendar reminders: import [calendar_reminders.ics](calendar_reminders.ics) into Google Calendar.

---

## ✍️ Signature

Your handwritten signature photo was processed: rotated upright, lined-paper background and ruled lines removed, exported as transparent PNG (`assets/signature.png`). The same signature image is embedded in the signature area of every task PDF (starting with Task 2). Original-colour version kept as `signature_original_color.png` for authenticity.

---

## 🚀 How to push this to GitHub (no token needed in chat)

**Option A — Web upload (safest, 2 minutes):**
1. Go to github.com → New repository → name: `workora-pharmacovigilance-internship` → Public → Create
2. Click "uploading an existing file" → drag the whole folder contents (or use GitHub Desktop)
3. Commit message: `Workora PV internship — Task 2 PDF + signature + repo structure`

**Option B — GitHub Desktop / VS Code:** Clone the empty repo, copy this folder's files in, Commit & Push.

**Option C — Command line (only if you want me to push for you):**
Create a **fine-grained** token (Settings → Developer settings → Personal access tokens → Fine-grained tokens) with:
- Repository access: only this repo
- Permissions: Contents: Read & write
- Expiration: **30 days** (as you planned) — then delete it after pushing
⚠️ **Do NOT paste a classic token with full `repo` scope in chat.** If you do share a token, revoke it immediately after the push. I will never store it in the repo (`.gitignore` blocks credential files).

---

## 📅 Reminders

- Import `calendar_reminders.ics` to Google Calendar — daily 9:00 AM (Africa/Lagos) reminders, one per task day.
- GitHub: each push lights up your contribution calendar. Aim for a commit every working day (even a README update counts).
- Optional GitHub Action in `.github/workflows/` can auto-create a reminder issue each Monday — enable it after first push if you want it.

---

*Signed: Emmanuel Ademola — 21 November 2026*
