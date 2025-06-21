# 📻 SDR Experiments Collection

A collection of beginner Software Defined Radio (SDR) experiments using **GNU Radio** and **RTL-SDR v4** dongles. These projects explore basic SDR concepts including signal acquisition, filtering, demodulation, and signal visualization.

## 🎯 Project Overview

This repository contains starter SDR experiments created while learning GNU Radio fundamentals. Each experiment focuses on different radio reception scenarios and demonstrates basic signal processing workflows.

## 🧪 Experiments

### [`first/`](first/README.md) - Basic FM Radio Receiver
Simple FM radio receiver demonstrating fundamental SDR processing chain with spectrum visualization.

### [`fm-radio/`](fm-radio/README.md) - FM Radio with Dual Visualization  
FM radio receiver with frequency spectrum and waterfall displays, plus adjustable volume control.

### [`ham-radio/`](ham-radio/README.md) - HAM Radio Receiver for 2m Band (144-148 MHz)
Amateur radio receiver adapted for VHF band with narrowband FM demodulation and adjustable filtering.

## 🛠️ Hardware Requirements

- **RTL-SDR v4 Dongle** (or compatible RTL-SDR device)
- **Antenna** appropriate for target frequencies
- **Computer** with GNU Radio installed

## 📚 Software Dependencies

- **GNU Radio** (3.8+ recommended)
- **SoapySDR** with RTL-SDR support
- **Python 3** with GNU Radio Python bindings

## 🚀 Getting Started

1. **Install GNU Radio and dependencies**
2. **Connect your RTL-SDR v4 dongle**
3. **Navigate to any experiment folder**
4. **Open the `.grc` file in GNU Radio Companion**
5. **Generate and run the flowgraph**

## 📊 Frequency Coverage

- **FM Radio:** 85-108 MHz (commercial FM broadcast band)
- **HAM Radio:** 144-148 MHz (2-meter amateur radio band)

## 📝 Documentation

Each experiment folder contains:
- Block explanations and configurations
- Signal flow diagrams
- User interface screenshots
- Parameter descriptions
- Learning objectives
