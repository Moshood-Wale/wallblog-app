# The Wall Blog Application

This is a Flask-based web application for a blogging platform.

## Prerequisites

- Python 3.x installed on your system.
- `pip` package manager installed.

## Installation

1. Clone the repository:

   git clone https://github.com/Moshood-Wale/wallblog-app.git
   
   cd flaskblog  

2. Set up a virtual environment:

   python -m venv venv  # Create a virtual environment

3. Activate the virtual environment:
 
    source venv/bin/activate

4. Install dependencies:

   pip install -r requirements.txt

## Configuration

1. Set up your environment variables:
   
   Create a `.env` file in the root directory with the contents of the .env_sample already provided.

   Replace `your_secret_key`, `your_email@example.com`, and `your_email_password` with appropriate values.

## Running the Application

1. Initialize the database:

   python run.py

   This will create the necessary database tables and start the Flask development server.

   By default, the application will be accessible at `http://localhost:5000`.

3. Open your web browser and navigate to `http://localhost:5000` to view the application.
