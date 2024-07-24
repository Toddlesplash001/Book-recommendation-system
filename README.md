# Book Recommender System

## Project Overview

The Book Recommender System is a Python-based application designed to suggest books to users based on their previous ratings. This system uses a combination of collaborative filtering techniques and cosine similarity to recommend similar books to a given book title. It processes user and book data to build a recommendation engine that can be used to find books similar to a given title.

## Features

- **Data Loading**: Reads user, book, and rating data from CSV files.
- **Data Cleaning**: Handles missing and duplicate data.
- **Recommendation Engine**: Uses cosine similarity to recommend similar books.
- **Web Interface**: A Flask-based web interface allows users to input a book title and receive recommendations.

## Requirements

- Python 3.7+
- Flask
- Pandas
- Scikit-learn
- Numpy

## Installation

1. **Clone the Repository**

   ```bash
   git clone <repository-url>
   cd book-recommender
2. **Install Dependencies**

Create a virtual environment (recommended) and install the required packages:

bash
Copy code
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
Prepare Data

3. **Ensure the following CSV files are in the data/ directory:**

Users.csv
Books.csv
Ratings.csv
Run the Application

4. **Start the Flask server:**

bash
Copy code
python book-recommender.py
Open your browser and navigate to http://127.0.0.1:5000 to access the web interface.

## Usage

Navigate to the Web Interface

Open your web browser and go to http://127.0.0.1:5000.

Enter a Book Title

Input the title of a book in the form provided and submit.

View Recommendations

The system will display a list of books similar to the entered book title.

## Code Explanation

book-recommender.py: The main Python script that implements the recommendation algorithm using cosine similarity and sets up the Flask web server.
index.html: The HTML template for the web interface.
style.css: CSS file for styling the web interface.
Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

