# OCR-UI: Optical Character Recognition User Interface

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-orange)
![Tesseract](https://img.shields.io/badge/Tesseract-OCR-lightgrey)
![Flask](https://img.shields.io/badge/Flask-2.0%2B-yellowgreen)
![License](https://img.shields.io/badge/License-MIT-green)

A user-friendly web interface for Optical Character Recognition (OCR) built with Flask, OpenCV, and Tesseract OCR. Extract text from images with customizable preprocessing options.

![OCR-UI Demo](demo.gif) <!-- Replace with actual demo gif/path -->

## Features

- 📷 **Image Upload**: Supports JPG, PNG, and PDF file formats
- 🛠 **Preprocessing Options**:
  - Grayscale conversion
  - Thresholding (Binary, Otsu, Adaptive)
  - Noise reduction
  - Edge detection
- 🔍 **OCR Engine**: Powered by Tesseract OCR with multiple language support
- 📤 **Export Results**: Download extracted text as .txt file
- ⚙ **Configurable Settings**: Adjust OCR parameters for optimal results

## Installation

### Prerequisites
- Python 3.8+
- Tesseract OCR ([Installation Guide](https://github.com/tesseract-ocr/tesseract))
- Poppler (for PDF support - `brew install poppler` on Mac, `sudo apt-get install poppler-utils` on Linux)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/kirankumarkv/OCR-UI.git
   cd OCR-UI

2. Install Dependencies
pip install -r requirements.txt

3. Configure Tesseract path in config.py if not in system PATH:
TESSERACT_PATH = "/usr/local/bin/tesseract"  # Update this path

4. Run the application:
python app.py

5. Access the UI at http://localhost:5000

**Usage**
1. Upload an image or PDF file
2. Select preprocessing options
3. Adjust OCR parameters (language, page segmentation mode)
4. Click "Extract Text"
5. View results and download as needed

 
