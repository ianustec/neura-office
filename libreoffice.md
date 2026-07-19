# LibreOffice / OpenOffice

NEURA Office writes **Office Open XML** (OOXML): `.docx`, `.pptx`, `.xlsx`.
That is the same family of formats Microsoft Office and LibreOffice both open.

## What works today

| Format | LibreOffice | Typical gaps |
|--------|-------------|--------------|
| `.docx` | Good | Fancy covers, some header graphics, exact font metrics |
| `.xlsx` | Good | Charts and conditional formatting can look different |
| `.pptx` | Partial | Native charts, icons-in-shapes, complex layers |

LibreOffice does **not** need to run inside the Open WebUI container.
The tools write the file; you open it later in LibreOffice (or Excel / Word).

## Honest policy

- We optimize for Microsoft Office first (largest ask from Open WebUI users).
- We keep OOXML so LibreOffice stays in scope.
- We will publish a QA pack (sample files + notes) when the matrix is tested.
- We will not claim “100% LibreOffice identical” without evidence.

## Help us

Open an issue on this hub with:

- LibreOffice version
- OS
- Which tool / sample file
- Screenshot of the mismatch

That feeds the Next phase in [`ROADMAP.md`](ROADMAP.md).
