# Stock Phrase Auto-Selector

## Overview

The **Stock Phrase Auto-Selector** is a Python-based tool built to make life easier for RAs by helping them pick the right stock phrases based on specific metadata combination. It’s designed to run in Google Colab and uses an Excel file (`Stock Phrase Auto-selector_test.xlsx`) containing the necessary data for processing.

For now, I’ve been testing it with just the B1 and B2 indicators in Nature Methodology because their scoring logics for stock phrases is already in a more code-friendly format. The tool currently supports two types of logics: AND and NOT EQUAL TO.

## Contents

- `Stock Phrase Auto-selector_test.xlsx`: Excel file containing elements, metadata, and corresponding stock phrases.
- `sp_auto_selector.py`: Python script developed for Google Colab to process the Excel file and provide an interactive interface for users.
- `README.md`: This documentation file.

## Getting Started with Google Colab

To utilize the tool within Google Colab:

1. **Access Google Colab**:
   - Navigate to Google Colab: https://colab.research.google.com/drive/19nPajRhgB0Em4fZyRMGFcmikh4KOpdqo?usp=sharing

2. **Upload the Excel File**:
   - Click on the folder icon in the left sidebar.
   - Use the **Upload** button to select and upload `Stock Phrase Auto-selector_test.xlsx` from your local computer.

3. **Run the Script**:
   - Execute the code cell within the notebook to initialize the tool.

4. **Use the Tool**:
   - Use the provided dropdown menus to select elements and metadata.
   - The tool will display the corresponding stock phrase based on your selections.

## Notes

- The tool is designed for use within Google Colab, so if you’re running it locally, you might need to tweak a few things.
- You are welcome to expand the test file by adding more stock phrases. However, please ensure that any new entries adhere to the correct format and include all required data to guarantee accurate processing.

## License

This project is licensed under the MIT License.

## Author

Xuelai Wang - Initial work - (mail to: x.wang@worldbenchmarkingalliance.org)
