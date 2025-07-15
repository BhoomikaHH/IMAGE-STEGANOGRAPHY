# 🖼️ Image Steganography

This project implements **Image Steganography**, a technique used to hide secret messages inside images without noticeably altering the visual content.  
It uses the **Least Significant Bit (LSB)** method to embed and retrieve data, ensuring secure and discreet communication.

---

## 🚀 Features

- 🔐 Hide and extract text messages within images
- 🧠 LSB (Least Significant Bit) based steganography algorithm
- 🖼️ Supports common image formats like PNG and JPEG
- 💡 Simple and effective implementation for learning and experimentation

---

## 💻 Tech Stack

- **Python 3**
- **Pillow (PIL)** – For image processing
- *(Optional: Flask/Tkinter/CLI depending on your implementation)*

---

## 📂 Project Structure

```bash
📁 image-steganography/
├── encode.py         # Script to embed secret message
├── decode.py         # Script to extract message
├── stego.py          # Main runner or combined logic (if applicable)
├── sample_images/    # Input/output image samples
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation
