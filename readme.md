

# Word Unprotection Tool for macOS

## Introduction
The Word Unprotection Tool is a simple application designed to remove protection from Word documents. It supports batch processing of multiple Word files and offers a user-friendly interface for selecting files and setting output options.

## Features
- Supports selecting individual or multiple Word files.
- Supports selecting folders containing Word files.
- Customizable output directory and filename format.
- Processes both DOCX and DOC files.
- Displays processing logs and progress bar.
- User-friendly graphical interface.




## Installation
1. Ensure you have Python 3.x installed on your macOS system.
2. Download or clone this project.
3. Install the required dependencies:
   ```bash
   pip install tk
   brew install libreoffice
   ```

## Usage
1. Run the program:
   ```bash
   python word_unprotection_tool.py
   ```
2. In the interface, click "Select Word File" or "Select Folder" to choose the Word files you want to process.
3. Choose output settings. You can select to use the same directory as the source files or specify a custom output directory.
4. Set the output filename format (use "Original Filename" to represent the original file name).
5. Click "Start Conversion" to begin processing the files.
6. After processing is complete, you can view the results in the log area.

## Notes
- Ensure you have permission to access and modify the selected Word files.

## Contributions
Contributions are welcome! If you find any bugs or have suggestions for improvements, please submit an issue or pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

**Note**: Replace the download link with the actual URL for the macOS version release.