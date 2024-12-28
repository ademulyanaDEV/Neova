REGISTER https://drive.neova.io/my-drive
But you need access to the code first because this is a private testnet.
JOIN NEOVA DISCORD FOR GET CODE ACESS : https://discord.gg/S2BUpT4b
---

# Random File Generator

This program generates random files of various types and sizes. It allows users to specify the number of files, the type of files (TXT, CSV, PDF, DOCX, or NFT), and the desired size of the files. The files are stored in a folder named `TEMPLATE_FILE`.

## Features

- **Generate Files**: Supports generating files of different types (TXT, CSV, PDF, DOCX, and NFT).
- **Random Content**: The content of each file is randomly generated, including random strings for text-based files and random pixel art for NFT files.
- **File Size**: Each file is generated to a specific size, which can be set (default is 1 MB).
- **Directory Management**: Files are saved in a folder called `TEMPLATE_FILE` (created if it doesn’t already exist).

## Prerequisites

Before running the program, make sure the following libraries are installed:

- `fpdf` (for PDF file creation)
- `PIL` (for generating NFT images)
- `python-docx` (for DOCX file creation, optional)

Install the required libraries using the following commands:

```bash
pip install fpdf
pip install pillow
pip install python-docx
```

## How to Run

1. Clone or download the repository containing the script.
2. Open a terminal or command prompt.
3. Navigate to the directory where the script is located.
4. Run the script using Python:

```bash
python random_file_generator.py
```

5. Follow the on-screen prompts to:
   - Enter the number of files to create.
   - Choose the file type (TXT, CSV, PDF, DOCX, or NFT).
   - The program will generate the files in the `TEMPLATE_FILE` directory.

## File Types

- **TXT**: Creates a text file with random alphanumeric content.
- **CSV**: Creates a CSV file with random alphanumeric data.
- **PDF**: Generates a PDF file with random text.
- **DOCX**: Generates a Word document with random text (requires the `python-docx` library).
- **NFT**: Generates a 500x500 pixel image with random colored rectangles, simulating an NFT image.

## Customization

- **File Size**: By default, files are created with a size of 1 MB. You can modify the `file_size_mb` variable in the `main()` function to change the size.
- **Folder Name**: The folder where files are saved is `TEMPLATE_FILE`, but you can modify this in the code.

## Example Output

The program will create files in the `TEMPLATE_FILE` folder. Here is an example of the folder structure after running the program:

```
TEMPLATE_FILE/
    1_XmTj5sQd7F.txt
    2_5dftHh7Kd8.csv
    3_QWZB1vTfA5.pdf
    4_RGhD2LyJb2.docx
    5_KCdZ5Wx9n0.png
```

## Troubleshooting

- **Missing `python-docx` Library**: If you try to generate DOCX files without having the `python-docx` library installed, you will see an error message. Install it using `pip install python-docx`.
- **Permission Issues**: Make sure you have permission to create files and directories in the location where you're running the script.

---
