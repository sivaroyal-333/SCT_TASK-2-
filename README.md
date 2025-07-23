# SCT_TASK-2-
#  Image Encryption-Decryption Tool

This repository contains a simple yet effective **Image Encryption-Decryption tool** developed as part of my **SkillCraft Technology Internship Task 02**.

---

##  **Project Objective**

To build a Python program that can **encrypt and decrypt images** by manipulating their pixel values using a custom user-defined key. This ensures basic security for image data and demonstrates practical applications of array operations in Python.

---

##  **Tech Stack**

- **Python**
- **NumPy** for pixel value manipulation
- **Pillow (PIL)** for image loading and saving
- **Jupyter Notebook** for demonstration and explanation

---

##  **How It Works**

1. **Encryption**
   - Adds a key value to each pixel (RGB) value in the image.
   - Uses modulo 256 to wrap around pixel values within [0, 255].

2. **Decryption**
   - Subtracts the key value from each pixel to restore the original image.

---

