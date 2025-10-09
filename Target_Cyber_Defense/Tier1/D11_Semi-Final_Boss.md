# D11. Semi-Final Boss
**Objective:** Find one suspicious registry key

**Difficulty:** Medium (300 points)

**Category:** Windows Forensics

## Materials and References
- **Provided:**
    - Registry hive: `hklm.system.hiv`
    - Resource link: [Windows Registry Forensics Cheat Sheet](https://www.cybertriage.com/blog/windows-registry-forensics-cheat-sheet-2025/)
- **Tools Used:**
    - Terminal
    - `hivexsh`
    - grep
    - RegRipper3.0
- **References:**
    - [hivexsh](https://man.archlinux.org/man/hivexsh.1.en)
    - [RegRipper3.0](https://github.com/keydet89/RegRipper3.0)
    - [hid documentation](https://learn.microsoft.com/en-us/windows-hardware/drivers/ddi/_hid/)

## Flag Format
**Format:** registry key path

Example: `HKCU\Software\Policies\Microsoft\Windows\WindowsCopilot\TurnOffWindowsCopilot`

Submission is regex-matched, so as long as the path is correct, it will be accepted.

## Write-Up