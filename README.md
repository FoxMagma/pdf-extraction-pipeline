# PDF Data Extractor: Tables + Graphs to Excel/CSV

**Extract tables, financial data, and graphs from PDFs to clean Excel/CSV files.**

## Features

- Extracts tables from any PDF (even scanned or complex layouts)
- Preserves rows, columns, and data exactly as in the original
- Exports to Excel (`.xlsx`) or CSV (`.csv`)
- Extracts graphs/charts as PNG images
- Handles large documents (100+ pages, 100+ tables) 

## How It Works

1. PDF is processed page by page
2. Tables are detected and extracted
3. Data is cleaned and aligned
4. Output is saved to Excel/CSV
5. Graphs are saved as PNG files

## Requirements

```bash
pip install pdfplumber pandas openpyxl
