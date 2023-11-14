# JPG to PNG Converter

## Overview

The **JPG to PNG Converter** is a Python tool designed to convert JPG files to PNG format. The tool allows you to specify the source folder path (in my case it is "Pokedex") and the output folder where the converted PNG files will be saved. The conversion is carried out using the [Pillow](https://pillow.readthedocs.io/en/stable/) library, a powerful image processing library for Python.

## Requirements

- Python 3.x
- Pillow library

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Ryan-Naughty/jpg-to-png-converter.git
   cd jpg-to-png-converter
   ```

2. **Install Pillow:**
   ```bash
   pip install Pillow
   ```

## Usage

1. **Run the Converter:**
   - Execute the following command in the terminal, specifying the source folder path and the output folder:
     ```bash
     python JPGtoPNGconverter.py (pokedex_path) (output_folder)
     ```
     - Replace `(pokedex_path)` with the path to the folder containing the JPG files.
     - Replace `(output_folder)` with the path where you want to save the converted PNG files.

2. **Example:**
   - To convert JPG files in the "Pokedex" folder and save them in the "Output" folder, run:
     ```bash
     python JPGtoPNGconverter.py Pokedex Output
     ```

## Notes

- Ensure that Python is installed on your system before running the tool.
- The tool assumes that the source JPG files are organized in a folder named "Pokedex" by default.

## About Pillow

[Pillow](https://pillow.readthedocs.io/en/stable/) is an actively maintained fork of the Python Imaging Library (PIL). It provides easy-to-use methods for opening, manipulating, and saving various image file formats. The library is widely used for image processing tasks in Python.

**Note:** Make sure to replace "your-username" in the clone URL with your actual GitHub username if you decide to fork and clone the repository.
