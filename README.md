# RebootReady — Offline Recovery Assistant

RebootReady is a Windows desktop prototype that helps users prepare for Windows troubleshooting and recovery.

## Prototype features
- Local recovery guidance and a readiness checklist that saves progress.
- Basic Windows and device information.
- Optional export of installed third-party driver packages using Windows PnPUtil.
- Local diagnostic logging and support-bundle export.
- PowerShell scripts for launch-stability checks and mock-only QA scenarios.

## Build
The app uses WPF and .NET 8. To build it, use Windows 10/11 with the .NET 8 SDK or Visual Studio 2022 with the .NET desktop development workload.

**This repository currently contains the project overview, not the complete application source package.** The v0.4.0 source ZIP still needs to be uploaded to this repository.

## Safety and limitations
This is an early prototype, not a production Windows installer or recovery tool. It does not automatically reinstall or repair Windows, restore drivers, or create bootable recovery USB media. It is not a compiled executable and has not been verified on Windows in this environment. Test recovery-related changes in a disposable virtual machine first.

See [RebootReady project details](REBOOTREADY_PROJECT.md) for more information.
