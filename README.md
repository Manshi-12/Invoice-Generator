# Invoice Generator

## Description
A Python-based invoice generator that creates invoices in PDF format and stores customer details in a PostgreSQL database. The system includes features for customer management such as adding, searching, and deleting customer records. The project is implemented using Python and integrates with PostgreSQL for data storage.

## Project Structure
This repository contains the Jupyter Notebook (`.ipynb`) file for the project implementation. It is designed to run directly in a Jupyter Notebook environment.

### Features:
- **Customer Management**: Add, search, and delete customer information.
- **Invoice Generation**: Create invoices in PDF format with itemized details.
- **Database Integration**: Stores customer details in PostgreSQL database.

## Requirements:
- Python 3.x
- Jupyter Notebook or JupyterLab
- `psycopg2` (for PostgreSQL connection)
- `fpdf` (for PDF generation)
  
You can install the required packages using:
```bash
pip install psycopg2 fpdf
```
## Setup Instructions:
1. Clone the repository.
2. Open the Invoice_Generator.ipynb file in a Jupyter Notebook environment.
3. Follow the on-screen instructions in the notebook to run the project.

## Database Setup:
This project uses PostgreSQL for storing customer details. Make sure you have a PostgreSQL database running and configure the connection parameters in the notebook accordingly.
