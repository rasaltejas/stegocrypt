# 🔒 StegoCrypt

### Hide Secret Messages Within Images Using Advanced Steganography

StegoCrypt is a modern, web-based steganography tool that allows you to securely hide text messages inside images using the Least Significant Bit (LSB) technique. All processing happens locally in your browser - no server uploads required!

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://rasaltejas.github.io/stegocrypt/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/rasaltejas/stegocrypt)

---

## ✨ Features

- **🔐 LSB Steganography**: Uses Least Significant Bit technique to hide messages invisibly within images
- **⚡ Real-time Processing**: Instant encoding and decoding directly in your browser
- **🎨 No Visible Changes**: Messages are embedded without altering the image appearance
- **📊 Analytics Dashboard**: Shows capacity usage, message length, and processing statistics
- **💾 Multiple Format Support**: Works with PNG, JPG, and BMP image formats
- **🔒 Complete Privacy**: All processing happens client-side - nothing leaves your device
- **📱 Responsive Design**: Beautiful UI that works on desktop, tablet, and mobile
- **🚀 Zero Dependencies**: Pure HTML, CSS, and JavaScript - no frameworks required

---

## 🎯 How It Works

### Encoding Process
1. **Upload an Image**: Select or drag-drop an image file
2. **Enter Your Message**: Type the secret message you want to hide
3. **Capacity Check**: System automatically checks if your message fits
4. **Encode**: Click "Hide Message" to embed the text using LSB steganography
5. **Download**: Save the encoded image with your hidden message

### Decoding Process
1. **Upload Encoded Image**: Select the image containing the hidden message
2. **Extract**: Click "Extract Message" to decode the hidden text
3. **View Message**: The secret message is revealed and displayed

### Technical Details

StegoCrypt uses **Least Significant Bit (LSB) steganography**:
- Each pixel has RGB color channels (Red, Green, Blue)
- Each channel is represented by 8 bits (0-255)
- The algorithm modifies the least significant bit of each channel
- This creates imperceptible changes to the human eye
- Message is terminated with a delimiter (`|||END|||`) for accurate extraction

**Capacity Calculation:**

https://rasaltejas.github.io/stegocrypt/
