# Roadmap

Public roadmap for **NEURA Office**. Dates are indicative; status beats dates.

## Now (shipped)

- [x] Generate Documents (`.docx`) for Open WebUI
- [x] Generate Slides (`.pptx`) for Open WebUI
- [x] Generate Spreadsheets (`.xlsx`) for Open WebUI
- [x] MIT, single-file tools, community listings
- [x] Company letterhead for Word (`.docx` / `.dotx`, chat or `/mnt/uploads`)

## Next

- [ ] Shared design tokens / accent story across the three tools
- [ ] LibreOffice QA pack: open sample files in LO 24.x, document gaps
- [ ] Badge matrix on this hub (Office / LibreOffice / Google Sheets)
- [ ] More Word templates and letterhead examples
- [ ] Spreadsheet polish (named styles, pivot-friendly sheets)
- [ ] Slide theme packs and example decks

## Later

- [ ] **NEURA for Microsoft 365** (see [`apps/ms365.md`](apps/ms365.md))
  - Word / Excel / PowerPoint / Outlook add-in
  - Open WebUI as the assistant backend
  - Same generation engines behind a Copilot-shaped UX
- [ ] Optional Outlook mail draft / attachment flow
- [ ] Hardening for air-gapped / on-prem only deployments

## Won't do

- Bundle all tools into one giant `.py` (hurts install and maintenance)
- Claim pixel-perfect LibreOffice parity without a tested matrix
- Put private NEURA deploy configs in this public hub

## Suggest something

Open a Discussion or Issue on this repo, or on the component that fits.
