---
layout: post
title: Image‑Based Steganographic Encryption
description: Modular encryption + LSB image embedding using XOR, Caesar & Vigenère ciphers
skills:
  - Python
  - NumPy
  - PIL/Pillow
  - Matplotlib
  - Cryptography
  - Steganography
main-image: /assets/projects/steganography_demo.png
---

## 🔐 Project Overview
Describe how this tool encrypts user-provided plaintext with either XOR, Caesar or Vigenère ciphers, converts it to binary, embeds it into a grayscale or RGB image via least-significant-bit steganography, and optionally visually compares encoded vs original image using a diff tool.

## 🧪 Technical Approach
- Modular cipher architecture (xor(), caesar(), vigenere())
- `text_to_binary()` with custom start/end sequences and offset-based control
- `encode_msg()` algorithm treating grayscale & RGB differently
- `compare_images()` using Matplotlib to generate a visual diff heatmap
- Full CLI user interface in `main.py`

## ⚙️ Skills & Tools
- **Python** scripting and modular code structure
- **NumPy** & **Pillow (PIL)** for image data handling
- **Matplotlib** for binary image diff visualization
- Implementation of classical cipher techniques and LSB steganography
- CLI UX and file I/O error handling
- Collaborative code development following academic integrity guidelines

## 👥 Team Contribution
Project built as part of Purdue’s ENGR 133 class (Assignment 11.1.1 Demo 1) by Lisette Mak, Olivia Varmo, Tavish Leslie, Divya Wadhwa — clearly defined roles in encryption logic, image processing, code cleanup, and documentation.

## 🖼️ Visual Demo
{% include image-gallery.html images="projects/steganography_demo.png, projects/steganography_encoded.png, projects/steganography_diff.png"%}

## 📚 Report
Full technical write-up is available in the repo as [`report.pdf`](./report.pdf). Includes background, design decisions, examples, and results.

## 🧠 Impact & Applicability
This project illustrates the intersection of classical cryptography and digital watermarking. Its modular design can be extended to more advanced encryption, larger cover media, and real-world applications in secure data transmission—showcasing creative problem-solving and systems thinking attractive to engineering internship recruiters.

