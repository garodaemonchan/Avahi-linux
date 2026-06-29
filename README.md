
# Avahi Linux

> A lightweight, user-friendly Linux distribution focused on simplicity, speed, and modularity.

## Overview

Avahi Linux is an independent Linux distribution designed around a simple idea:

> **Deliver a modern desktop and server experience without unnecessary complexity.**

Rather than relying on heavyweight components, Avahi Linux embraces a minimal userspace while preserving a comfortable experience for both newcomers and experienced Linux users.

The project aims to provide a clean foundation that stays close to traditional Unix principles without sacrificing usability.

---

## Philosophy

Avahi Linux is built on the following principles:

- Minimal by design
- Modular instead of monolithic
- Fast boot and low resource usage
- Easy to install and maintain
- Predictable behavior
- User-friendly without excessive abstraction

Every component is selected for a reason. If a simpler solution exists, it is usually preferred.

---

## Core Technologies

Current implementation:

- **init:** dinit
- **core utilities:** BusyBox
- **installer:** NetBSD curses-based installer
- **C library:** glibc

Planned:

- musl edition
- Additional package repositories
- Improved hardware support
- Desktop-oriented installation profiles

---

## Why dinit?

Avahi Linux uses **dinit** instead of larger init ecosystems.

Benefits include:

- Extremely fast startup
- Straightforward service management
- Small codebase
- Easy configuration
- Minimal dependencies

---

## Why BusyBox?

BusyBox provides a compact and efficient userspace while significantly reducing the system footprint.

This allows Avahi Linux to remain lightweight without compromising everyday functionality.

---

## Installation

The installer is based on the classic **NetBSD curses installer**, providing a fast and keyboard-friendly installation process.

No graphical installer is required, making installation possible even on older hardware or remote terminals.

---

## Editions

### glibc Edition

The current stable edition.

Recommended for:

- Desktop users
- General-purpose systems
- Maximum software compatibility

### musl Edition *(Planned)*

A future release focused on:

- Smaller binaries
- Lower memory usage
- Increased simplicity
- Static-friendly environments

---

## Goals

- Create a lightweight Linux distribution that remains practical for daily use.
- Avoid unnecessary system complexity.
- Keep the operating system understandable.
- Maintain excellent performance on both modern and older hardware.
- Provide a consistent and predictable user experience.

---

## Project Status

Avahi Linux is currently under active development.

Interfaces, package management, and system components may change as the project evolves.

Community feedback is always welcome.

---

## Contributing

Contributions, bug reports, feature requests, and discussions are greatly appreciated.

Whether you are a developer, package maintainer, documentation writer, or tester, your help is valuable.

---

## License

Avahi Linux is released under the GNU General Public License v2.0 (GPL-2.0).

This project follows the same licensing philosophy as the Linux kernel, ensuring that improvements and derivative works remain free software while preserving users' rights to study, modify, and redistribute the source code.

For the full license text, see the LICENSE file.

Codeberg repo: https://codeberg.org/garodaemon/Avahi-linux
