# OCR - Example

This repository contains an example of how to use python
to process text from images/pdfs.
The example consists of taking a PDF of a scanned book, turning
each page into an image, and then applying the pre-trained Tesseract
model with the `layoutparser` package.

## Installing Tesseract

In order to run this example, one need to install
Tesseract. Assuming you are using Ubuntu/Linux, the
following commands will install Tesseract:
```
sudo apt install tesseract-ocr
sudo apt install libtesseract-dev
sudo apt install tesseract-ocr-por
```

The last line is installing the OCR for Portuguese.
