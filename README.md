# 📚 eBook to PDF Converter (Google Colab)

A feature-rich **Python-based eBook to PDF Converter** designed to run entirely in **Google Colab**. The project converts multiple eBook formats into high-quality PDF documents while allowing users to customize the output according to their preferences.

This repository contains two versions of the project:

- **Version 1.0** – A simple, beginner-friendly implementation demonstrating the complete conversion workflow.
- **Version 2.0** – A modular, production-style implementation with interactive customization, validation, progress tracking, and detailed reporting.

---

# ✨ Features

## 📖 Supports Multiple eBook Formats

- EPUB
- MOBI
- AZW3
- FB2
- LIT
- PRC
- CBZ
- CBR
- TXT
- HTML
- DOCX
- RTF
- and other formats supported by **Calibre**

---

## 🎨 PDF Customization

Users can customize the generated PDF by selecting:

- Paper Size
- Page Margins
- Base Font Size
- PDF Font Size
- Paragraph Spacing
- Text Justification

---

## ⚙️ Interactive Workflow

Version 2.0 provides an interactive command-line interface that guides the user through the entire conversion process.

Features include:

- User-friendly prompts
- Input validation
- Configuration management
- Error handling
- Conversion summary
- Download-ready output

---

## 📊 Progress Tracking

The conversion process displays:

- Progress bar
- Conversion stages
- Execution time
- Status updates

---

## 📋 Detailed Conversion Report

After successful conversion, the application displays:

- Input file name
- Output PDF name
- File size
- Conversion status
- Time taken
- Output verification

---

# 📂 Repository Structure

```
.
├── Ebook_to_PDF_Converter.ipynb          # Version 1.0
├── EBook_to_PDF_Converter_V2_0.ipynb     # Version 2.0
└── README.md
```

---

# 🚀 Project Versions

## Version 1.0

A straightforward implementation demonstrating:

- Installing Calibre
- Uploading an eBook
- Detecting file format
- Converting to PDF
- Downloading the generated PDF
- Basic PDF customization

Ideal for beginners who want to understand the complete conversion workflow.

---

## Version 2.0

A significantly improved and modular implementation.

### Project Modules

- Project Skeleton
- Configuration Manager
- Dependency Manager
- Interactive User Preference Module
- Upload & Validation Module
- Command Builder Module
- Conversion Engine
- Progress Manager
- Verification & Conversion Report
- Main Controller

This version follows a cleaner software architecture and is much easier to maintain and extend.

---

# 🛠️ Technologies Used

- Python
- Google Colab
- Calibre (ebook-convert)
- subprocess
- pathlib
- threading
- tqdm
- shutil
- os

---

# ▶️ Getting Started

1. Open either notebook in **Google Colab**.
2. Run all cells sequentially.
3. Install Calibre when prompted.
4. Upload an eBook.
5. Configure PDF preferences.
6. Start the conversion.
7. Download the generated PDF.

---

# 📸 Workflow

```
Upload eBook
      │
      ▼
Detect File Format
      │
      ▼
Validate Input
      │
      ▼
Choose PDF Settings
      │
      ▼
Build Conversion Command
      │
      ▼
Convert using Calibre
      │
      ▼
Verify Output
      │
      ▼
Generate Report
      │
      ▼
Download PDF
```

---

# 🎯 Learning Objectives

This project demonstrates practical software engineering concepts such as:

- Modular programming
- User input validation
- Configuration management
- Error handling
- File management
- External command execution
- Progress monitoring
- Report generation
- Interactive application design

---

# 📌 Future Improvements

Potential future enhancements include:

- GUI version using Streamlit
- Batch conversion
- Drag-and-drop uploads
- OCR support for scanned documents
- Password-protected PDFs
- Custom fonts
- Table of contents generation
- Metadata editing
- Image compression options
- Cloud storage integration

---

# 🤝 Contributions

Contributions, suggestions, and improvements are always welcome.

Feel free to fork the repository and submit a pull request.

---

# ⭐ If You Found This Project Useful

If this repository helped you, consider giving it a ⭐ to support the project.
