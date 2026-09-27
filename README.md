# PCSpec Portable

PCSpec Portable is a lightweight Windows hardware and system-information utility designed to present useful information clearly without becoming a Device Manager-style information dump.

**Current version:** PCSpec Portable v3.0

## Features

PCSpec organises local Windows hardware and system information into focused sections:

- **Summary** for essential specifications at a glance
- **Detailed** for core computer, Windows, CPU, RAM, graphics and storage information
- **Extra** for additional physical hardware such as battery, LAN, Wi-Fi, audio, USB ports and displays
- **Full Report** for a complete combined technical report
- **Others** for advanced Windows-level, status and diagnostic information
- **About** for product, privacy, version and build information

Additional capabilities include battery health reporting where available, physical USB-port filtering, LAN and Wi-Fi identification, display information, TPM reporting, staged loading, and copy/save functions.

## Download

- [Windows EXE](https://github.com/tajuddinkh/PCSpec/raw/main/Portable/PCSpec_Portable_v3.0.exe)
- [Portable ZIP](https://github.com/tajuddinkh/PCSpec/releases/download/v3.0/PCSpec-Portable-v3.0-Portable.zip)

No installation is required. Download the EXE or Portable ZIP, extract if necessary, and run `PCSpec_Portable_v3.0.exe`.

## Interface

The interface is organised into six top-level pages: Summary, Detailed, Extra, Full Report, Others and About. The Summary uses a restrained card layout for quick reading, while the report pages provide progressively deeper technical information without mixing every Windows device into the main view.

## Privacy

PCSpec Portable operates locally on the computer. It:

- uses no telemetry
- uses no analytics
- uses no cloud services
- performs no online update checks
- performs no internet hardware or vendor lookup
- does not scan nearby Wi-Fi networks
- does not transmit hardware, system or user information

Hardware and system information is obtained from local Windows sources such as WMI/CIM, SMBIOS/firmware, the Registry and local Windows APIs.

## Portable operation

PCSpec requires no installation and does not install a Windows service or continuously monitor the computer in the background. It is designed to run as a lightweight portable Windows utility.

## System information accuracy

PCSpec reports information exposed by Windows, installed drivers and system firmware. Some details may be unavailable when the manufacturer, firmware or driver does not expose them reliably. PCSpec is designed not to guess hardware characteristics that cannot be established with reasonable confidence.

## Integrity

Final v3.0 executable SHA-256:

`F3EC9AF0D76C1FF94C87B86D57E2A6ED1D8D86EB2B1B3A7DD06DC2131457C9D1`

Checksums for the public downloads are provided in [`SHA256SUMS.txt`](SHA256SUMS.txt).

## Developer

Designed and developed by **Tajud Din**.
