# 🖼️ Steganography Tool for Image/File Hiding  

## Overview  
This project focuses on hiding and extracting secret messages inside images using **Least Significant Bit (LSB) steganography**.  
It ensures secure communication by embedding text (and later small files) into **lossless images (PNG/BMP)** without visible distortion.  

The tool is built in **Python** with **Pillow, Stepic, and Tkinter**, and tested in **Parrot OS terminal**.  

---

## Steps Performed  

1. ✅ Set up Python environment and installed required libraries (`Pillow`, `stepic`, `tkinter`).  
2. ✅ Implemented backend functions to:  
   - Hide secret messages inside images.  
   - Extract hidden messages back from encoded images.  
3. ✅ Tested with PNG/BMP formats for accuracy.  
4. ✅ Verified successful embedding and extraction in Parrot OS.  

---

## Risks of Using Insecure Formats  

- ❌ **JPEG compression** can corrupt hidden data.  
- ❌ Using **low-quality images** may cause noticeable changes after encoding.  
- ❌ Large message sizes may **increase image file size significantly**.  

---

## 📸 Illustrations  

- 🖼️ **Original Image** → `input.png`  
- 🖼️ **Encoded Image with hidden message** → `output.png`  
- 📝 **Decoded Output** → `"Hello from Parrot OS!"`  

---

## Conclusion  

✅ Successfully built and tested backend encoding/decoding functions.  
✅ Messages were hidden and extracted securely without quality loss.  
✅ Next phase will focus on:  
- Adding **Tkinter GUI with drag-and-drop**.  
- Supporting **optional encryption** before embedding.  
- Extending support for **file hiding**.  

---

👨‍💻 **Author:** Harisha Mahadevappa  



