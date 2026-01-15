# LaTeX Tutorials 📘

Welcome to the **LaTeX Tutorials** repository. This collection documents my journey and practice in mastering LaTeX—the gold standard for scientific and technical documentation.

This repository covers everything from the very first lines of code to advanced applications, including mathematical formulas for AI/Data Science, complex research paper structures, and professional CV design.

## 📝 Repository Contents

Here is a breakdown of the source files included in this project:

### 1. Introduction to LaTeX (`main.tex`)
A starter file to understand the fundamental structure of a LaTeX document.
- **Key Concepts:**
  - Document classes, packages (Vietnamese support, margins).
  - Text formatting: **Bold**, *Italics*.
  - Creating lists (Itemize).
  - Simple inline math equations.

### 2. Basic Math & Graphics (`BaiTap2_BasicMath.tex`)
Focuses on presenting mathematical formulas commonly used by AI Engineers.
- **Key Concepts:**
  - Using `amsmath` and `graphicx` libraries.
  - Writing complex formulas: **Mean Square Error (MSE)**, Weight Matrices.
  - Inserting and captioning images (e.g., Loss Function visualization).

### 3. Reference Management (`BaiTap3.tex`)
Learn how to automate citations and bibliographies—an essential skill for academic research.
- **Key Concepts:**
  - Using `BibTeX` for managing references.
  - Writing a Literature Review with citations.
  - Formatting bibliographies using the IEEE standard (`ieeetr`).

### 4. Capstone/Research Report (`BaiTap4_Capstone.tex`)
A complete template for a Graduation Thesis or Research Paper.
- **Key Concepts:**
  - `report` document class usage.
  - Structural hierarchy: `Chapter`, `Section`, `Subsection`.
  - Advanced equations: Loss Functions (Content Loss, Adversarial Loss), PSNR metrics.
  - Creating comparison Tables.
  - Automatic Table of Contents and Cross-referencing.

### 5. Professional Resume (`CV_Resume.tex`)
Applying LaTeX to design a clean, professional, and ATS-friendly Curriculum Vitae.
- **Key Concepts:**
  - Advanced layout control with `geometry` and `multicol`.
  - Integrating icons via `fontawesome5`.
  - Defining custom commands for optimized data entry.
  - Structured presentation of Experience, Skills, and Projects.

---

## 🚀 How to Compile

To build these `.tex` files into PDFs, you can use:

1.  **Online:** [Overleaf](https://www.overleaf.com/) (Recommended for beginners). Simply upload the files and folders, then hit "Recompile".
2.  **Local:** Install **TeX Live** (or MikTeX) and use an editor like **VS Code** (with the *LaTeX Workshop* extension) or **TeXstudio**.

**Note:**
- Ensure that associated image files (e.g., inside `BaiTap2/` folder) and `.bib` files (for references) are present in the directory to avoid compilation errors.
- The CV file requires a compiler that supports specific fonts (standard `pdflatex` is usually sufficient).

---

## 🛠 Key Packages Used
The main libraries utilized in this repository include:
- `babel`: Vietnamese language support.
- `amsmath`, `amsfonts`: Advanced mathematical typesetting.
- `graphicx`: Image insertion.
- `geometry`: Page margin configuration.
- `cite`: Citation management.
- `fontawesome5`: Icons for social media/contacts (used in the CV).
- `hyperref`: Hyperlinks and navigation.

---

## 👤 Author

**Phạm Huỳnh Quý An**
- **Role:** AI Engineer, Data Scientist, Researcher
- **Education:** FPT University
- **Contact:** [LinkedIn](https://www.linkedin.com/in/quyan1907/) | [GitHub](https://github.com/PHQuyAn)

---
*Thank you for visiting this repository. If you find it helpful, please leave a ⭐️!*