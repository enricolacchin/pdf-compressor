# PDF Compressor

This Python script compresses PDF files in a specified directory and saves the compressed files in another directory.

## Requirements

To run the script, you will need:

- Python 3.6 or later
- Ghostscript installed on your system

## Installation

To install Ghostscript:

On Ubuntu:

```bash
sudo apt-get install ghostscript
```

On MacOs:

```bash
brew install ghostscript
```

## Usage

To use the script, you need to modify the `input_folder` and `output_folder` variables in the Python code to point to the correct folders on your system.


```python
input_folder = 'path/to/your/input/folder'
output_folder = 'path/to/your/output/folder'
```

Once you have set the folders, you can run the script with Python.

```bash
python compress_pdf.py
```

This will compress all the PDF files in the input folder and save the compressed files in the output folder.

## License

This project is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE).

Please refer to the license file for more information.

If you encounter any issues or have any questions, please open an issue in the GitHub repository.