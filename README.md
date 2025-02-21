# ToDo-List-using-Flask-and-MongoDB

## Description
This project is a simple To-Do List web application built using Flask (Python) and MongoDB. It is containerized using Docker with two services:
- A Flask-based web application.
- A MongoDB database for storing tasks.

## Features
- Add, update, and delete to-do tasks.
- Store tasks persistently using MongoDB.
- Containerized using Docker and orchestrated with Docker Compose.

## Prerequisites
Ensure you have the following installed:
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/your-username/ToDo-List-using-Flask-and-MongoDB.git
cd ToDo-List-using-Flask-and-MongoDB
```

### 2. Build and Run the Project
```sh
docker-compose up --build
```

This will:
- Build the Flask application container.
- Start the MongoDB container.
- Run the web application on `http://localhost:5000/`.

### 3. Stop the Project
To stop the containers, press `Ctrl + C` or run:
```sh
docker-compose down
```

## Project Structure
```
ToDo-List-using-Flask-and-MongoDB/
│── app.py                # Flask application
│── requirements.txt      # Python dependencies
│── Dockerfile            # Docker instructions for Flask app
│── docker-compose.yml    # Docker Compose configuration
│── templates/            # HTML templates
│── static/               # CSS, JavaScript files
└── README.md             # Project documentation
```

## Environment Variables
The application uses the following environment variable:
- `MONGO_URI`: The connection string for MongoDB (default: `mongodb://mongo:27017/todo_db`).

## Contributing
Feel free to fork this repository and submit pull requests for improvements.

## License
This project is open-source and available under the [MIT License](LICENSE).

# ToDo-List-using-Flask-and-MongoDB
