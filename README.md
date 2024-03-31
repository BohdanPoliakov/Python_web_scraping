# Euronics iPhone Data Retrieval

## Task

This software is designed to allow the user to easily retrieve information about iPhone products from the Euronics website. The task of this software is to enable the user to specify a specific iPhone model name and then the software will display all related products with their associated details. The application will display variants of the phone with similar names, offering the user a visual representation of the products, including an image, price and a link to the product. The software will also provide the possibility to create an Excel file containing all the products retrieved from the Euronics website.

## Python Libraries

The project uses several Python libraries:

- `requests` - Online data extraction.
- `BeautifulSoup` - HTML analysis and data extraction.
- `dataclasses` - Simple syntax for data classes.
- `xlsxwriter` - Creating Excel files and inserting data.

## Software Development Workflow

1. **Data Extraction:** Using `requests` and `BeautifulSoup`, data is extracted from the Euronics website.
2. **Data Processing:** The data is cleaned and formatted using functions such as `remove_extra_spaces`, `format_price` and `three_symbols_price`.
3. **Data Saving:** The function `create_excel_file` has been developed which saves the processed data in an Excel file.

## Videos How the Programme Works
Our Programme Activity Videos
Example:
https://failiem.lv/f/drushmgpj6

## Program Usage

You can use the program by entering a command in the terminal:

```bash
2.py "iphone_model"
Where "iphone_model" is the name of the desired iPhone model.

If you want to get information about iPhone 11 using the program, enter the following command:
python 2.py iPhone 11

## Library

To execute the program, you need to install the following dependencies:
pip install requests
pip install beautifulsoup4
pip install xlsxwriter


