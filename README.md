# Formatting Figure Captions in Word (ABNT)

This project aims to create a Python script to format figure title and captions in Microsoft Word according to ABNT standards (Brazilian Association of Technical Standards).

## Problem

ABNT requires the figure title and caption to be displayed on the same line with distinct formatting. However, Word does not offer a direct way to achieve this formatting.

## Solution

This Python script uses the `python-docx` library to automate the formatting of captions in Word. It allows:

* Inserting the figure title and caption on the same line.
* Applying different formatting to the title (bold, size 12) and the caption (non bold, size 10).
* Centering the caption paragraph.

## How to use

1.  **Install dependencies:**

    ```bash
    pip install python-docx
    ```

2.  **Run the script:**

    ```bash
    python tittle-and-sub-figure.py
    ```

3.  **Open the `formatted_caption.docx` file in Word.**

## Contribution

This project is open source and accepts contributions. Feel free to open issues and pull requests.

## Author

\[Tiago Nascimento]

## Notes

* This is a beginner project and is still under development.
* Any feedback and suggestions are welcome.
* The `python-docx` library handles `.docx` files, but not `.doc` files.