# Bookshelf Project

This project contains a Bookshelf backend API (Node.js/Hapi), a simple frontend, and Postman testing assets.

## Folder Structure 

```text
Bookshelf-Management-REST-API/
|- bookshelf-api/                                  # Main application folder (backend + frontend)
|  |- src/
|  |- frontend/
|  |- package.json
|- BookshelfAPITestCollectionAndEnvironment/       # Postman collection + environment
|- README.md
```

## Running the Backend API

1. Go to the backend folder:
	`cd bookshelf-api`
2. Install dependencies:
	`npm install`
3. Run the server:
	`npm run start`

## Running the Frontend

1. Open the `bookshelf-api/frontend` folder.
2. Open `index.html` directly in your browser or use Live Server.

## API Testing

- The Postman collection and environment files are stored in the `BookshelfAPITestCollectionAndEnvironment` folder.
- Import both files into Postman, then run the test requests.


