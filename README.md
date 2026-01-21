# Amlogic & AOSP Native Toolkit (Apple Silicon)

A fast, native toolkit for working with **Amlogic firmware packages** and **Android logical partitions**, built for **Apple Silicon (ARM64)** Macs.

---

## ✅ Included Tools

- **ampack** — Unpack and repack Amlogic `.img` firmware containers into partition files  
- **lpmake** — Native AOSP tool to build **logical partition** metadata/images (e.g., `super.img`)

---

## 🖥️ Apple Silicon Support

- **Native ARM64** build for **M1 → M5** (no Rosetta required)  
- Built and tested on Apple Silicon for smooth performance

---

## 🚀 Quick Start

### 1) Download & Extract
Download the `.zip` from the **Releases** section and extract it.

### 2) Make the binaries executable
In Terminal - run
"chmod +x ampack , lpmake"

---

### To unpack a firmware image
./ampack unpack <firmware>.img

---

### To build logical partitions
./lpmake <parameters>

---

# 📌 Notes

This project is intended for legitimate development, testing, and device maintenance on hardware you own or are authorized to service.
Please follow your device vendor’s policies and applicable laws.
