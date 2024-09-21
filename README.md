```markdown
# Automated PDF Data Extraction Tool

An advanced tool designed to automate the extraction and structuring of data from PDF files, converting unstructured information into organized Excel sheets. With robust multi-language support and high-accuracy checkbox recognition, this solution minimizes manual effort and enhances efficiency in data processing.

## Core Features
- **Text Extraction Automation**: Transforms unstructured text from PDFs into structured data within Excel files.
- **Checkbox Recognition**: Detects and logs checkbox inputs with precise accuracy.
- **Image Extraction**: Automatically identifies and extracts images embedded in PDF documents.
- **Multi-language OCR Support**: Facilitates OCR and translation for various languages, including English, Spanish, French, German, Chinese (Simplified), Malay, Tamil, and Hindi.
- **Streamlined Deployment**: Uses pyngrok for effortless deployment and accessibility.

## Technology Stack
- **Frontend**: Streamlit for an interactive web interface.
- **Backend**: Python
- **Libraries**: 
  - Text & Image Processing: PyMuPDF, pytesseract, pdf2image, Pillow
  - Data Handling: pandas, openpyxl
  - Advanced Image Processing: OpenCV
  - Translation & OCR: Google Translate API
  - Table Extraction: Camelot, Tabula
- **Deployment**: pyngrok for easy sharing and remote access.

---

# PDF to Excel Conversion

A powerful tool to extract data from multiple PDF documents, efficiently converting it into a single structured Excel file. This solution is built to handle multilingual documents and provides exceptional accuracy in text and checkbox recognition.

## Features
- **Batch Conversion**: Processes multiple PDFs and outputs structured data into a single Excel file.
- **Text and Checkbox Recognition**: Extracts both text and checkbox selections with high accuracy.
- **Multilingual OCR and Translation**: Supports a wide range of languages for OCR and translation.
- **Image Hyperlinking**: Automatically detects images and includes hyperlinks to them in the final Excel file.
- **Performance**: Achieves over 72% accuracy, reducing manual data entry by 80%.

---

## Key Achievements
- Processed **500+ PDFs** with over **82% accuracy** in text and checkbox recognition.
- Reduced manual data entry time by **80%**, enabling faster processing of large document sets.

---

## Installation & Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SanjanaReddySangam/Automated-PDF-Data-Extraction.git
   cd Automated-PDF-Data-Extraction
   ```

2. **Set Up Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

## How to Use
- Upload the PDFs to process.
- Choose the preferred OCR language.
- Download the final Excel file with extracted data.

---

## Contributing
We welcome contributions! Follow these steps:
1. Fork the repository.
2. Create a branch: `git checkout -b feature-branch`.
3. Make your changes and commit: `git commit -m 'Add new feature'`.
4. Push your branch: `git push origin feature-branch`.
5. Open a pull request.

## Acknowledgments
Special thanks to Sanjana for her invaluable support and contributions.

## Future Enhancements
- Improve image and checkbox extraction functionalities.

## Contact
For inquiries, please contact: kedharnadh800@gmail.com

## License
This project is licensed under the MIT License—please refer to the LICENSE file for more details.
