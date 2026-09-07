# TCPClient

VB6 Logon Client (`Logon Client.exe`) that gathers workstation logon info (WMI/WSH: user, host, MAC, OS, disk, memory) and talks to a logon server over the MS Winsock OCX to receive drive/printer mapping steps. Pair with sibling `TCPServer`. Open `Logon Client.Vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Client` (`Logon Client.Vbp`) | VB6 | WinForms exe | Logon client: send profile, map drives/printers |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Logon Client.Vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `Mswinsck.ocx`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/TCPClient`.
Company names in `.vbp` files: Unknown Organization.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
