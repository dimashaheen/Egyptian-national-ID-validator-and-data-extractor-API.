# Egyptian-national-ID-validator-and-data-extractor-API.

# Egyptian National ID Validator and Data-Extractor API

This project is a Django-based API that validates Egyptian national IDs and extracts relevant information such as birth date and governorate. It also includes features like rate limiting, API key authentication, and API call tracking.

---

## Features

1. **National ID Validation**:
   - Validates the structure and logic of Egyptian national IDs.
2. **Data Extraction**:
   - Extracts birth date and governorate from valid national IDs.
3. **Rate Limiting**:
   - Limits API usage to 100 requests per day per user.
4. **API Key Authentication**:
   - Requires an API key for access.
5. **API Call Tracking**:
   - Logs all API calls for future billing purposes.

---

## Requirements

- Python 3.8+
- Django 4.0+
- Django REST Framework (DRF)
- SQLite (default database)

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/dimashaheen/egyptian-national-id-api.git
   cd egyptian-national-id-api

Set Up a Virtual Environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install Dependencies:
pip install -r requirements.txt

Run Migrations:
python manage.py migrate

Start the Development Server:
python manage.py runserver
