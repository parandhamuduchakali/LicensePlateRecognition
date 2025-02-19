# License Plate Recognition

## Overview
This project implements a License Plate Recognition (LPR) system using deep learning and computer vision techniques. The system is designed to detect and recognize license plates from vehicle images or video streams.

## Features
- Automatic detection of license plates from images and videos.
- Optical Character Recognition (OCR) for extracting text from plates.
- Preprocessing techniques to enhance image quality.
- Integration with OpenCV and deep learning models for accurate results.

## Installation
To run this project, ensure you have the following dependencies installed:

```sh
pip install numpy opencv-python pytesseract tensorflow keras matplotlib
```

Additionally, you need to install Tesseract OCR:
- **Windows:** Download and install from [Tesseract OCR](https://github.com/UB-Mannheim/tesseract/wiki)
- **Linux/macOS:** Install via package manager (e.g., `sudo apt install tesseract-ocr`)

## Usage
### Running the Notebook
1. Open the Jupyter Notebook:
   ```sh
   jupyter notebook "License Plate Recognition.ipynb"
   ```
2. Run the notebook cells sequentially to process images and extract license plate information.

### Using as a Script
To run the script version, execute:
```sh
python license_plate_recognition.py --image input.jpg
```

## Output
- The system detects and highlights the license plate in the image.
- The extracted license plate text is displayed and saved as a text file.

## Future Improvements
- Implement real-time recognition using video streams.
- Improve OCR accuracy with deep learning models.
- Enhance image preprocessing for better detection in low-light conditions.

## License
This project is open-source and available under the MIT License.

