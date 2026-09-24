# Nat

VB6 NAT discovery and tooling suite bundled as one repo: Discover, Discover2, Broker, Ping, Collect, and Reader — each with its own `.vbp`. Open the relevant `.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Discover2` (`Discover2/prjDiscover2.vbp`) | VB6 | WinForms exe | 1. Load audit.xml (specifies the WMI classes to query).  2. Query classes and create output file. |
| `Discover` (`Discover/Discover.vbp`) | VB6 | WinForms exe | NAT Discover Process |
| `Broker` (`Broker/Broker.vbp`) | VB6 | WinForms exe | NAT Broker Process |
| `prjPing` (`Ping/Ping.vbp`) | VB6 | WinForms exe | NAT Ping Process |
| `Collect` (`Collect/Collect.vbp`) | VB6 | WinForms exe | NAT Collection Process |
| `Reader` (`Reader/Reader.vbp`) | VB6 | WinForms exe | NAT Reader Process |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Discover2/prjDiscover2.vbp`
- `Discover/Discover.vbp`
- `Broker/Broker.vbp`
- `Ping/Ping.vbp`
- `Collect/Collect.vbp`
- `Reader/Reader.vbp`

## Requirements

- Visual Basic 6.0 IDE

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Nat`.
Company names in `.vbp` files: Dave Robinson.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
