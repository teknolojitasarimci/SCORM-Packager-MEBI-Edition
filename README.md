# Glancer: AI-Powered SCORM Packager v5.0 (MEBİ Edition)

![App Screenshot](screenshot.png)

**Glancer SCORM Packager** is a powerful, AI-assisted desktop application designed to package HTML5 content into **SCORM 1.2** and **SCORM 2004** standards. This special edition is optimized for the **MEBI (Ministry of National Education)** content standards, ensuring seamless integration with educational LMS platforms.

Built for educators and developers, Glancer automates repetitive tasks, enhances accessibility, and leverages **Google Gemini AI** to intelligently grade and refine your content.

## 🚀 Key Features

*   **🤖 AI Integration (Google Gemini):**
    *   **Auto-Grading:** Intelligently injects scoring logic into standard HTML5 quizzes.
    *   **Smart Assistant:** Chat with the AI to refine code, fix CSS issues, or get accessibility advice directly within the app.
    *   **Smart Spell Check:** Automatically corrects typos and formatting errors (e.g., decimal commas, chemical subscripts).
*   **📦 Robust & Secure Packaging:**
    *   **Security First:** Active protection against Zip Bombs, Path Traversal attacks, and Symlink vulnerabilities.
    *   **Smart Entry Detection:** Automatically locates the correct `index.html` file, even in complex folder structures.
    *   **Encoding Fixer:** Automatically repairs broken character encodings (UTF-8, ISO-8859-9, etc.).
*   **🛠 Standardization Tools:**
    *   **One-Click Styling:** Apply the corporate orange/teal color palette and rounded design language instantly.
    *   **Mobile Ready:** Automatically adds responsive meta tags and CSS for perfect rendering on Phones and Tablets.
    *   **Accessibility Suite:** Inject a comprehensive accessibility menu (Dyslexia font, High Contrast, Text Resizing).
    *   **Content Shield:** Option to disable right-click, text selection, and developer tools to protect your IP.
*   **📊 SCORM Compliance:**
    *   Full support for **SCORM 1.2** and **SCORM 2004 (4th Ed)**.
    *   Seamless reporting of **Score**, **Completion Status**, and **Time Tracking** to any LMS (Moodle, Canvas, Blackboard, etc.).

## 🛠 Installation

1.  **Prerequisites:**
    *   Python 3.10 or higher
    *   Active Internet connection (required for AI features)

2.  **Clone the Repository:**
    ```bash
    git clone https://github.com/teknolojitasarimci/SCORM-Packager-MEBI-Edition.git
    cd SCORM-Packager-MEBI-Edition
    ```

3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: `PySide6-WebEngine` is recommended for the Live Preview feature)*

## ▶️ Usage

Launch the application via terminal:

```bash
python scorm_paketleyici_v5_MEBI_surumu.py
```

1.  **Select Source:** Choose a ZIP file, a Folder, or a single HTML file.
2.  **Configure:** Toggle options for Accessibility, Mobile View, Security, and AI analysis from the left panel.
3.  **AI Enhance (Optional):** Enter your API key to let Gemini AI analyze and auto-grade your content.
4.  **Package:** Click "Create SCORM Package" to generate your LMS-ready zip file.

## 🤝 Contributing

We welcome contributions! Please feel free to submit a Pull Request or open an Issue for bugs and feature requests.

## 📄 License

This project is open-source and available under the MIT License.

---
**Developed by:** Mürsel EREN (Glancer)
