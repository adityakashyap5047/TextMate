# 📝 TextMate

A Django-based web application that allows you to analyze and clean up your text with ease. This project provides functionalities such as removing punctuations, converting text to uppercase, removing newlines and extra spaces, and counting characters.

## 🚀 Features

- 🔤 **Remove Punctuations** – Clean your text by removing common punctuation marks.
- 🔠 **Convert to Uppercase** – Transform all characters in the text to uppercase.
- ↩️ **Remove Newlines** – Eliminate all newline characters from your text.
- ␣ **Remove Extra Spaces** – Normalize whitespace to a single space.
- 🔢 **Character Count** – Count all characters in the input text.

## 🛠️ Built With

- Python 3.x
- Django 4.x
- HTML/CSS (for templates)


## 📦 Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/textanalyzer.git
cd textanalyzer

# 2. Create and activate a virtual environment
python -m venv env

# On Windows
env\Scripts\activate

# On macOS/Linux
source env/bin/activate

# 3. Install Django
pip install django

# 4. Run database migrations (if applicable)
python manage.py migrate

# 5. Start the development server
python manage.py runserver

# 6. Open your browser and go to
# http://127.0.0.1:8000/
