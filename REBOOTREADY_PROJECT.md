# RebootReady — Offline Recovery Assistant

RebootReady is an early Windows desktop prototype to help users prepare for Windows troubleshooting and recovery.

## Prototype features
- Local recovery guidance and a readiness checklist that persists between launches.
- Basic device and Windows information.
- Optional export of installed third-party driver packages through Windows PnPUtil.
- Local diagnostic logging, support-bundle export, and mock-only QA scripts.

## Important limitations
This is source code for an early prototype, **not** a completed Windows installer or recovery product. It does not reinstall or repair Windows, automatically restore drivers, download missing drivers offline, or create bootable recovery USB media. Do not rely on it as your only backup or recovery method.

## Build requirements
- Windows 10/11
- .NET 8 SDK, or Visual Studio 2022 with the .NET desktop development workload

The v0.4.0 package is source code and scripts, not a compiled executable. Build and verify it on Windows before use. Test recovery-related behavior in a disposable virtual machine first.

## Source package
The full v0.4.0 source package is intended to be provided as `RebootReady_UserFocused_v0.4.0_Source.zip`. See the release/build notes in the source package for setup and validation details.
