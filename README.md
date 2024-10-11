# Simple Form

A simple form to take name and email and return them to check how to pass variables through the program.

## Prerequisites

Ensure you have the following installed:

- Python 3.8 or higher
- Flask and other dependencies (listed in requirements.txt)
- (Optional) Virtual environment tools like virtualenv or conda


## Installation

1. Clone the Repository:

```bash
git clone https://github.com/username/project-name.git
cd project-name
```

2. Create and Activate Virtual Environment (optional):

```bash
python -m venv venv
```
Activate on Windows: venv\Scripts\activate
Activate on macOS/Linux: source venv/bin/activate

3. Install Dependencies:

```bash
pip install -r requirements.txt
```

4. Set Environment Variables:

Create a .env file in the root directory and add:
```bash
FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=your_secret_key
```
5. Database Setup (if applicable):

```bash
flask db init
flask db migrate
flask db upgrade
```

## Running the Project

Start the Flask development server:
```bash
flask run
```
Visit http://localhost:5000 in your browser.

# Usage

You can interact with the application through the web interface or make API requests:
Example GET request:
```bash
curl http://localhost:5000/api/v1/resource
```
