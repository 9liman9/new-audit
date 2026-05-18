# new audit · نيو أوديت

Arabic-first audit-app prototype for Qatari accounting firms.

**Live demo:** https://9liman9.github.io/new-audit/

Single-file HTML application. No build, no server, no dependencies. Opens in any browser. State persists in `localStorage` + `IndexedDB`. Aligned with ISA standards (210, 220, 300, 315, 320, 500, 510, 520, 580).

## Status

| Version | Date | What's in it |
|---------|------|---------------|
| v3 (current `index.html`) | 2026-05-16 | Login → workspace → 6-section Planning → 18-area Execution → Completion → memo + mind-map. Vertical accordions, 4-level sign-off ladder, A4 print-ready engagement memo. |
| v4 (in progress) | 2026-05-18+ | Rebuilds Planning as 8-section tree with IC dropdowns + file uploads (IndexedDB). New TB import + mapping flow. Risk Assessment auto-populated from TB. Multi-year client filter. Merged auditor + client setup. |

## Usage

Just open `index.html` in a browser. Any username/password works.

## Tech

- Vanilla JavaScript + HTML + CSS (no frameworks)
- Hash-based routing
- localStorage state persistence
- IndexedDB for file attachments (v4+)
- Google Fonts inlined as base64 (works fully offline)
- RTL, Arabic-first

## Project

Built by [@9liman9](https://github.com/9liman9). Domain partner: Yazan Al-Awadat.

---

> برنامج التدقيق (نيو أوديت) — أداة مراجعة الحسابات لمكاتب التدقيق في قطر. ملف HTML واحد، يعمل بدون إنترنت أو خادم. يدعم معايير المراجعة الدولية ISA.
