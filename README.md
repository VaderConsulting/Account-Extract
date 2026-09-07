# Account Extract

VB6 Domain Accounts / Users & Groups extractor (`AccountExtract.exe`) that enumerates users, groups, and computers from a domain controller via Active DS/WMI and can export results (v1 `UserExtract.vbp` plus `V2/`). Open either `.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `AccountExtract` (`UserExtract.vbp`) | VB6 | WinForms exe | Enumerate domain users/groups/computers |
| `AccountExtract` (`V2/AccountExtract.vbp`) | VB6 | WinForms exe | V2 of domain account extract |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `UserExtract.vbp`
- `V2/AccountExtract.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSCOMCTL.OCX`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Account Extract`.
Company names in project files: CSC.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
