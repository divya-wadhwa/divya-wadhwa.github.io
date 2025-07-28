---
layout: post
title: Image‑Based Steganographic Encryption
description: Modular steganography tool combining encryption (XOR, Caesar, Vigenère) with LSB image embedding
skills:
  - Python
  - NumPy
  - PIL / Pillow
  - Matplotlib
  - Cryptography
  - Steganography
main-image: /assets/projects/steganography_demo.png
---

## 🔐 Project Overview
A Python-based system to encrypt messages using XOR, Caesar, or Vigenère ciphers and embed them into images via least significant bit (LSB) steganography for secure message transmission.

## 🧪 Technical Approach
- Modular implementation of classical cipher techniques
- Custom binary markers (start/end sequences) and bit offset control
- Grayscale and RGB image LSB embedding via `encode_msg()`
- Image diff visualization using `compare_images()`

## ⚙️ Skills & Tools
- **Languages**: Python
- **Libraries**: NumPy, Pillow (PIL), Matplotlib
- **Concepts**: Cryptography, Steganography, Binary Data Encoding, CLI UX

## 🖼️ Visual Demo
{% include image-gallery.html images="projects/steganography_demo.png, projects/steganography_encoded.png, projects/steganography_diff.png" height="400"%}

## 📘 Report
Download the full technical report: [report.pdf](./report.pdf)

## 👥 Team & Contributions
This project was completed as part of Purdue’s ENGR 133 assignment by:
- Lisette Mak
- Olivia Varmo
- Tavish Leslie
- Divya Wadhwa

## 🧠 Applications & Future Work
The tool showcases practical cryptography and image-based data hiding. It can be extended to color images, larger data payloads, advanced encryption, and real-world watermarking use cases.
