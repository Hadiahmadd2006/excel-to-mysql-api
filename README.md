# Excel to MySQL API

A FastAPI application that processes Excel files and imports them into MySQL database.

## Setup

1. Install dependencies:
```bash
pip install fastapi uvicorn jinja2 python-multipart mysql-connector-python openpyxl
```

2. Configure MySQL connection in `sql_imports.py`

3. Run the application:
```bash
python sql_imports.py
```

4. Access the web interface at: http://localhost:8000

## Features

- Excel file upload via web interface
- Automatic table creation from Excel sheets
- Data validation and sanitization
- Error handling and logging
