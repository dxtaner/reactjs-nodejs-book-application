
Books App Backend
=================

This is the backend for a simple Books App, built using Node.js, Express, and MongoDB.

Getting Started
---------------

### Prerequisites

Before you begin, ensure you have the following installed:

*   Node.js: [Download Node.js](https://nodejs.org/)
*   MongoDB: [Install MongoDB](https://docs.mongodb.com/manual/installation/)

### Installation

1.  Clone the repository:

        `git clone https://github.com/your-username/books-app-backend.git`
        `cd books-app-backend`
    

2.  Install dependencies:

        `npm install`
    

3.  Set up environment variables:

        `PORT=3033             MONGODB_URI=mongodb+srv://your-username:your-password@cluster0.guofsiq.mongodb.net/books-app`
        
    

Replace `your-username` and `your-password` with your MongoDB Atlas credentials.

Usage
-----

1.  Start the server:

        `npm start`
    

The server will run on `http://localhost:3033` or the port specified in the `.env` file.

2.  Test the API:

Visit `http://localhost:3033` in your browser or use tools like [Postman](https://www.postman.com/) to test API endpoints.

API Endpoints
-------------

*   `GET /`: Returns a welcome message.
*   `GET /books`: Returns a list of all books.
*   `GET /books/:id`: Returns details of a specific book.
*   `POST /books`: Creates a new book.
*   `PUT /books/:id`: Updates details of a specific book.
*   `DELETE /books/:id`: Deletes a specific book.

Contributing
------------

Feel free to contribute to this project by opening issues or submitting pull requests.

License
-------

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
