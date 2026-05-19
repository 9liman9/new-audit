# new audit · نيو أوديت

Arabic-first audit-app prototype for Qatari accounting firms.

**Live demo:** https://9liman9.github.io/new-audit/

Single-file HTML application. No build, no server, no dependencies. Opens in any browser. State persists in `localStorage`. Aligned with ISA standards (210, 220, 300, 315, 320, 500, 510, 520, 580).

## Status

| Version | Date | What's in it |
|---------|------|---------------|
| **v4 (current `index.html`)** | 2026-05-19 | Rebuilt after 2026-05-18 meeting + two new Excels. Login → Dashboard (year filter + client cards) → merged Auditor+Client setup → TB import + mapping → 7-section Planning tree → Execution stub. New IC dropdown UX (يوجد / لا يوجد / ينطبق / لا ينطبق) + auto file-upload slot when answer is "exists". Risk matrix auto-filtered by TB mapping. 86 IC questions + 11 meeting-minutes templates + 8 PF questions + 115 risk rows extracted verbatim from Yazan's Excels. |
| v3 (archived) | 2026-05-16 | Login → workspace → 6-section Planning → 18-area Execution → Completion → memo + mind-map. Vertical accordions, 4-level sign-off ladder, A4 print-ready engagement memo. |

## Usage

Open the live link in any browser. Any username/password works — or click **"تحميل بيانات عميل تجريبي"** at the bottom of the login screen to auto-seed a Qatari construction-co demo (Gulf Contracting LLC, FY 2025, balanced 27-row TB) and see the app populated end-to-end.

## Tech

- Vanilla JavaScript + HTML + CSS (no frameworks)
- Hash-based routing
- `localStorage` state persistence
- File attachments stub: filename + size stored only (no bytes yet — backend swap planned)
- Google Fonts via CDN (Amiri, Noto Naskh Arabic, IBM Plex Mono, IBM Plex Sans Arabic)
- RTL, Arabic-first

## Project

Built by [@9liman9](https://github.com/9liman9). Domain partner: Yazan Al-Awadat.

---

> برنامج التدقيق (نيو أوديت) — أداة مراجعة الحسابات لمكاتب التدقيق في قطر. ملف HTML واحد يعمل في أي متصفح. يدعم معايير المراجعة الدولية ISA.
