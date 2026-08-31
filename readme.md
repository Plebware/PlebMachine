# 🔑 PlebMachine 1.30.08.26

**RELEASE STATUS: TESTED DEVELOPMENT RELEASE — 2026-08-31**

PlebMachine is a state-driven Linux desktop orchestration system designed to provide structured working environments through modes, application launching, desktop configuration, wallpapers, and system-state management.

Version **1.30.08.26** is the current development release and has now passed a significant cross-distribution installation test.

## 🔑 1.30.08.26 — Major Test Milestone

The `plebmachine_1.30.08.26_amd64.deb` package was installed successfully on:

- **MX Linux 25.2**, Xfce.
- **SparkyLinux 8.4 (Seven-Sisters)**, Xfce, based on Debian 13 Trixie.

On SparkyLinux, the package installed **without manual intervention** and PlebMachine worked immediately after installation.

This is an important portability milestone: PlebMachine is no longer being tested only against its original MX Linux development environment.

## What Has Been Tested

The current package has been exercised through the PlebMachine desktop environment, including its core control and state-management components.

The SparkyLinux test demonstrated that the Debian package can be installed on a separate Debian/Xfce distribution and operate without requiring an MX-specific installation procedure.

Further testing of individual modes, supporting applications, and long-term stability remains part of development.

## 🧠 What Is PlebMachine?

PlebMachine is a **Linux desktop orchestration layer**. It does not attempt to replace the desktop environment. Instead, it works with the desktop to establish controlled working states around the user's tasks.

The project is built around:

- **State-driven operation.**
- **Modular components.**
- **Separation of system logic and user configuration.**
- **Recoverability and restoration of the user's original desktop state.**
- **Practical operation on lightweight Linux systems.**

## 🖥️ Cognitive Modes

PlebMachine is designed around task-oriented desktop modes, including:

- Everyday.
- Author.
- Study.
- Research.
- Graphics.
- Music.
- Video.
- Broadcast.
- AI Helpers.
- Developer.
- Accounting.
- Leisure.

The intention is simple: instead of forcing the user to manually prepare the desktop for every kind of work, PlebMachine prepares a controlled environment appropriate to the selected mode.

## ⚙️ Core Components

The current PlebMachine system includes components such as:

- **PlebMachine Mission Control** — central desktop orchestration.
- **PlebMachine Tools** — supporting configuration and maintenance tools.
- **PlebMachine User Setup** — user-oriented setup functions.
- **PlebMachine Gizmo** — application launching and mode selection.
- **Workspace orchestration** — controlled PlebMachine workspace environments.
- **Wallpaper and desktop-state management.**

## 🔐 User State Matters

One of the central design principles of PlebMachine is that the user's original desktop configuration must not simply be destroyed when PlebMachine takes control.

PlebMachine is intended to establish a **temporary controlled desktop state**, while preserving the user's original state underneath it.

When PlebMachine is switched OFF, the original desktop configuration should be restored.

This state-driven approach is fundamental to the project's architecture.

## 🧪 Testing Philosophy

PlebMachine is deliberately being tested on more than one Linux distribution.

The current development testing includes:

| Platform | Result |
| --- | --- |
| MX Linux 25.2 Xfce | Tested |
| SparkyLinux 8.4 Xfce | **Installed and working immediately** |

The SparkyLinux result is particularly useful because it provides an independent Debian/Xfce environment rather than another installation of the same distribution.

## 📦 Installation

The primary distribution package is:

```text
plebmachine_1.30.08.26_amd64.deb
```

Install the Debian package using your distribution's normal package-management tools.

The package is intended for **64-bit Debian-family Linux systems with Xfce**. Compatibility with other desktop environments and distributions remains subject to testing.

## ⚠️ Development Status

PlebMachine 1.30.08.26 is a **development/testing release**.

The successful MX Linux and SparkyLinux tests are encouraging, but the project remains under active development. Supporting applications such as GIMP, Logseq, LibreOffice, browsers, and other mode-specific software are installed separately and are not automatically considered part of the PlebMachine core.

Users testing the system should report problems, unexpected behaviour, or distribution-specific issues so that they can be investigated before a future stable release.

## 🔧 Development Direction

Current development priorities include:

- Cross-distribution testing.
- Clean-user installation testing.
- Workspace state preservation and restoration.
- Reliable mode transitions.
- Application-launch integration.
- Improved dependency handling.
- Clear separation between PlebMachine core and optional supporting applications.
- Continued testing on older and resource-limited hardware.

## 🛠️ Project Philosophy

PlebMachine follows a simple principle:

> **The computer should adapt to the user, not force the user to adapt to the computer.**

The project is intentionally being developed as a practical, understandable, and recoverable desktop layer rather than a collection of opaque automation tricks.

## 📚 Release Documentation

Detailed release notes for version 1.30.08.26 are available in:

`releases/1.30.08.26.md`

## Previous 1.0.0 Release

PlebMachine 1.0.0 was withdrawn after clean-user testing exposed a critical Mission Control and workspace-initialisation failure. That release should **not** be used.

Version 1.30.08.26 represents the subsequent development and testing work and should be treated as the current development package.

---

**Plebware — The workshop is open.**
