# QR_code_generator
The QR Code Generator for Excel allows users to create QR codes from data in Excel files. It reads specified columns, generates QR codes containing structured information with headers, and outputs a new Excel file with the original data and corresponding QR codes for easy sharing and scanning.

## Description
This project allows users to generate QR codes for data stored in an Excel file. It reads data from specified columns in an Excel sheet, creates QR codes based on this data, and outputs an Excel file with the original data alongside the generated QR codes. The QR codes contain detailed information formatted with headers, making it easy to understand the encoded data when scanned.

## Features
- Read data from Excel files and generate QR codes for each row.
- QR codes are created based on the combined values of multiple columns, including an index.
- Generated QR codes are saved as images and inserted back into the Excel file.
- Images are sized appropriately for easy scanning.
- The output Excel file retains the original data along with the corresponding QR codes.

## Table of Contents
- [Installation](#installation)
- [Google Colab](#GoogleColab)
## GoogleColab
You can  run this project in Google Colab: [Open Colab Notebook](https://colab.research.google.com/drive/17OKGI_LG0o1EnVKE6JLQZ9IPhIfxpAPt?usp=sharing)

## Installation
To set up the project, clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/qr-code-excel-generator.git
cd qr-code-excel-generator
pip install pandas qrcode[pil] openpyxl


