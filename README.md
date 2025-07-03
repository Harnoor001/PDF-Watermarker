# 🖋️ PDF Watermarker (Text + Image) – Google Colab

This Google Colab tool allows you to watermark PDF files with both custom **text** and an **image/logo**. No installation is required — everything runs directly in the cloud!

---

## ✅ Features

- 📄 Upload any PDF
- 🔠 Add **custom text watermark** (your message, name, "CONFIDENTIAL", etc.)
- 🖼️ Add an **image watermark** (like a logo or stamp)
- 📍 Choose exact **X-Y position** for both text and image
- 📏 Set **font size** and **image size**
- 🔁 Applies watermark to **all pages**
- 📥 One-click download of the final watermarked PDF

---

## 🛠️ Tech Stack

- Python 3  
- [PyPDF2](https://pypi.org/project/PyPDF2/) – for PDF reading/writing  
- [ReportLab](https://pypi.org/project/reportlab/) – for drawing the text/image watermark  
- Google Colab – to run everything without setup

---

## ▶️ How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload your **PDF** file and **image** (logo or stamp)
3. Enter:
   - Watermark **text**
   - **Font size** and **position** for text
   - **Position** and **size** of the image
4. The tool will apply the combined watermark to all pages
5. Download the final file from `/content/text_image_watermarke
