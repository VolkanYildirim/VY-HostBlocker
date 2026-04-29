# 🛡️ VY-HostBlocker

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Status](https://img.shields.io/badge/Status-Legacy_Code-blue?style=for-the-badge)

A desktop-based utility developed in C# designed to act as a local DNS sinkhole. By manipulating the Windows `hosts` file, it effectively blocks access to specific URLs, unwanted telemetry servers, and tracking domains at the system level.

### ⚙️ Security & Privacy Philosophy (Privacy-First)
- **Telemetry Prevention:** The tool was initially built to stop background tracking and data harvesting from proprietary software (e.g., stopping unauthorized `.io` telemetry domains).
- **Local Execution Only:** Operates entirely offline with zero external API calls. Your blocked lists remain strictly on your local machine.

### 🚀 Key Features
- Simple, lightweight Graphical User Interface (GUI) for non-technical users.
- Persistent blocking via system-level configuration.
- *Upcoming (V2 Roadmap):* Architecture refactoring and modernization of the UI/UX.

### 🔧 Build & Run
**Note:** Because this application modifies system-level network configuration files (`System32\drivers\etc\hosts`), it requires **Administrator Privileges (UAC)** to function correctly.

1. Clone the repository and open `STBlocker.sln` using Visual Studio.
2. Build the solution (`Ctrl + Shift + B`).
3. Run the compiled `.exe` as Administrator.
