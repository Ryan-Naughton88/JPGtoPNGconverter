# JPG to PNG Converter

## Overview

The **JPG to PNG Converter** is a Python script that converts JPG files in a specified folder into PNG files. The script utilizes the Pillow library for image processing.

## Features

1. **Conversion:**
   - Converts JPG files in a specified folder to PNG format.

## Usage

1. **Command Line Arguments:**
   - The script takes two command line arguments:
     - `path`: The path to the folder containing JPG files.
     - `directory`: The directory where converted PNG files will be saved.

2. **Output Directory Creation:**
   - If the specified output directory does not exist, it will be created.

3. **Conversion Process:**
   - Iterates through each JPG file in the specified folder.
   - Opens the JPG file using Pillow.
   - Saves the image as a PNG file in the specified output directory.

4. **Prints Status:**
   - Prints "all done!!" after completing the conversion process.

## Requirements

- Python 3.x
- Pillow library

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ryan-Naughton88/jpg-to-png-converter.git
   cd jpg-to-png-converter
   ```

2. **Install required libraries:**
   ```bash
   pip install pillow
   ```

3. **Run the script:**
   ```bash
   python JPGtoPNGconverter.py [path] [output_directory]
   ```

## Notes

- Ensure that the Pillow library is installed before running the script.
- The script takes two command line arguments: `path` and `output_directory`.
- The output directory will be created if it does not exist.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the terms of the license.

---
