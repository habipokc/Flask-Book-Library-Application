# Flask-Book-Library-Application
This is a Flask application that allows users to add books to a library and store them in a SQLite database. Users can view the list of books in the library, add new books, and assign ratings to each book.

Prerequisites
To run this application, you need to have the following installed:

-Python (version 3.7 or higher)
-Flask
-Flask-SQLAlchemy

Installation

-Clone this repository to your local machine or download the ZIP file and extract it.
-Open a terminal or command prompt and navigate to the project directory.
-Create a virtual environment (optional but recommended).
-Install the required dependencies by running the following command:
    pip install -r requirements.txt
 
Usage 
-In the project directory, run the following command to start the Flask development server:
    python app.py
-Open your web browser and go to http://localhost:5000 to access the application.

How It Works
-The main page (index.html) displays a list of books in the library along with their titles, authors, and ratings.
-To add a new book, click on the "Add Book" link.
-Fill in the book details in the form, including the title, author, and rating.
-Click the "Add" button to add the book to the library.
-The new book will be saved in the SQLite database.
-You will be redirected to the main page, where the updated list of books will be displayed.
-You can click on the book titles to view more details about each book.

File Structure
-app.py: The main Flask application file that handles routing and database operations.
-templates/: Directory containing HTML templates used by Flask to render web pages.
-index.html: The template for the main page that displays the list of books.
-add.html: The template for the form page where users can add a new book.
-mybooks.db: The SQLite database file that stores the book data.

Database Model
The application uses a Book model to define the structure of the books table in the database. The Book model has the following attributes:

-id: An auto-incrementing integer primary key for each book.
-title: A string field representing the title of the book (maximum length: 250 characters).
-author: A string field representing the author of the book (maximum length: 250 characters).
-rating: A float field representing the rating of the book.

Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

