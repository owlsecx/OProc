# 🦉 OProc

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.0-cyan?style=flat-square"/>
</p>

> **OProc** — Process Behavioral & Memory Forensic Analyzer ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OProc is a process behavioral and memory forensic analyzer for Linux. It tracks process trees, maps sockets and open files, extracts memory strings and can dump process memory for authorized forensic analysis. It also includes a lightweight intrusion-detection mode.

---

## ✨ Features

- Process-tree tracking with socket and open-file mapping
- Memory string extraction and process memory dump
- Live process watching by PID
- Environment scan for secret-like keys
- Namespace and cgroup inspection per PID
- Two-PID comparison, IDS mode and JSON/HTML export

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OProc --batch 1234
./OProc --watch 1234
./OProc --compare 1000 2000
./OProc --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
