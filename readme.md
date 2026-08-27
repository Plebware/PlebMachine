# 🚨 PlebMachine 1.0.0 — DO NOT DOWNLOAD

**RELEASE STATUS: WITHDRAWN FOR INVESTIGATION — 2026-08-27**

> ⚠️ **IMPORTANT: Please do not download or install PlebMachine 1.0.0 until further notice.**
>
> A fresh-user installation test has uncovered a **critical release bug** affecting the PlebMachine desktop orchestration system. **Mission Control does not initialise correctly, and the expected 12-workspace environment is not being established as intended.**
>
> The published `plebmachine_1.0.0_amd64.deb` package should therefore be considered **faulty and withdrawn** while the problem is investigated.

## What Happened?

PlebMachine 1.0.0 was released before sufficient clean-user installation testing had been completed.

During subsequent testing, we discovered that:

- **PlebMachine User Setup** works.
- **PlebMachine Tools** works.
- **PlebMachine Mission Control** does not initialise correctly.
- The expected **12-workspace environment** is not established correctly.
- The complete desktop orchestration system therefore cannot currently be considered reliable.

This is a **critical release bug**, and we are treating it seriously.

## What Should You Do?

**Do not download or install PlebMachine 1.0.0 until further notice.**

If you have already installed version 1.0.0, please do not rely on it as a production system. We are investigating the failure and will provide a corrected release when clean-user testing confirms that the complete system is functioning correctly.

## We Apologise.

PlebMachine 1.0.0 was published too soon. That is our mistake.

We would rather be completely open about the failure than allow people to install a system that does not perform as advertised.

The project is not abandoned.

**The workshop is open. The bug has been found. Now we fix the machine.**

---

# PlebMachine Development Status

PlebMachine is a state-driven Linux desktop orchestration system designed to provide structured working environments through modes, application launching, desktop configuration, wallpapers, and system-state management.

The project remains under active development and testing.

The previous development-status material below is retained as historical information; it should not be interpreted as the current release status.

---

## ⚙️ Historical Core Foundation

- Mode system concept defined.
- Initial CLI structure established.
- Basic mode switching logic implemented.
- Core directory structure designed for modular expansion.
- State-handling concepts introduced.

---

## 🧠 System Direction

PlebMachine is evolving into a **state-driven Linux productivity layer**, designed to:

- Separate system logic from user intent.
- Enable structured modes of operation.
- Provide predictable workflow environments.
- Act as a modular control layer over the desktop.

---

## 🔧 Current Development Priority

The immediate priority is **clean-user installation testing and correction of the Mission Control/workspace initialisation failure**.

A new release will only be announced after the corrected system has been properly tested.
