# 🚗 Detailing Auto Care SA - Job Manager

A Progressive Web App (PWA) for managing automotive detailing jobs, built for **Collision Works SA** and **Detailing Auto Care SA**.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

## ✨ Features

### 🔧 Job Management
- **Vehicle Registration** tracking with SA plate format support
- **VIN Number** capture via compliance plate scanning
- **Make & Model** auto-detection
- **Build/Compliance Date** extraction
- **Work Required** documentation
- **Photo Documentation** (8 slots: Front, Rear, Left, Right, Interior, Damage, Engine, VIN Plate)

### 📸 Camera & OCR
- **Real-time OCR** using Tesseract.js (runs entirely in browser)
- **Registration Plate Scanning** - Point camera at rego plate to auto-fill
- **Compliance Plate Scanning** - Extracts VIN, build date, and vehicle make
- **Photo Capture** with automatic compression (1200px max, ~70% quality)
- Works offline after initial load

### ⚠️ Priority Queue System
Jobs are automatically sorted by urgency:

1. **🔴 URGENT (Red)** - Over 5 days old without completion date (flashing alert)
2. **🔵 DATED (Blue)** - Has completion date (sorted by due date, oldest first)
3. **⚪ NORMAL (Silver)** -
