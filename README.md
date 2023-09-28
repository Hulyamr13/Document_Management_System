# Document Management System

This Python project is a Document Management System that allows you to find, organize, and store Word, Excel, and PDF files into a PostgreSQL database.

## Features

- Automatically finds Word (.docx), Excel (.xlsx), and PDF (.pdf) files in a specified directory.
- Extracts content from these files and stores it in a PostgreSQL database.
- Organizes files by type and allows for easy retrieval of document content.

## Requirements

1. Python (version 3.6 or higher)
2. Required Libraries:
    - `python-docx` - for handling Word files
    - `openpyxl` - for processing Excel files
    - `PyPDF2` - for working with PDF files
    - `psycopg2` - for connecting to a PostgreSQL database

## Installation

1. Clone this repository to your local machine.

2. Install the required libraries using `pip`:

