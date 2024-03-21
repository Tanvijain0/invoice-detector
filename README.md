
# Invoice Detector

## Overview

The Invoice Detector is a Python-based application designed to detect and extract invoice information from images or PDF documents. The application utilizes computer vision techniques and optical character recognition (OCR) to identify regions of interest within the document and extract relevant data such as invoice number, date, total amount, etc.

## Features

- Invoice Detection: Automatically locates invoices within images or PDF files.
- Region of Interest Extraction: Identifies key regions within the invoice document, such as headers, tables, and footers.
- Text Extraction: Uses OCR to extract text from the identified regions of interest.
- Information Parsing: Parses the extracted text to retrieve invoice details such as invoice number, date, total amount, etc.
- User Interface (Optional): Provides a user-friendly interface for uploading documents and viewing extracted information.

## Installation



 Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Ensure that you have Python installed on your system (version >= 3.6).

2. Navigate to the project directory:

    ```
    cd invoice-detector
    ```

3. Run the application:

    ```
    python invoice_detector.py
    ```

4. Follow the on-screen instructions to upload an image or PDF containing the invoice.

## Configuration

- Modify `config.py` to adjust settings such as OCR engine, confidence thresholds, etc.

## Dependencies

- OpenCV: [link](https://opencv.org/)
- Tesseract OCR: [link](https://github.com/tesseract-ocr/tesseract)

## Contributing

Contributions are welcome! If you have suggestions for improvements or encounter any issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

