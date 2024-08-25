# Blog API

This project features a simple Blog API with both a backend API and a frontend interface, all within the same codebase. It allows users to create, edit, view, and delete posts.

## Project Structure

- **`/public`**: Contains static files and frontend assets.
- **`/views`**: Contains EJS templates for rendering HTML.
- **`/api`**: Contains the API server logic.
- **`/frontend`**: Contains the frontend server logic.

## Technologies Used

- Node.js
- Express
- Axios
- EJS (Embedded JavaScript templating)
- Body-parser

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Taran2005/Blog-Project.git
    cd Blog-Project
    ```

2. **Install Dependencies:**

    ```bash
    npm install
    ```

3. **Configuration:**

    Ensure that the API server and the frontend server are configured to run on their respective ports (3000 for the frontend and 4000 for the API). The API server URL should be correctly set in the frontend server code.

4. **Running the Servers:**

    Start the API Server:

    ```bash
    node server.js
    ```

    This will start the API server on http://localhost:4000.

    Start the Frontend Server:

    ```bash
    node index.js
    ```

    This will start the frontend server on http://localhost:3000.

## Usage

- View Posts: Access the frontend at http://localhost:3000 to see the list of posts.
- Create a New Post: Go to http://localhost:3000/new to create a new post.
- Edit an Existing Post: Navigate to http://localhost:3000/edit/:id to edit a post by its ID.
- Delete a Post: Use the frontend interface to delete posts.

## API Endpoints

- GET /posts - Retrieve all posts.
- GET /posts/:id - Retrieve a specific post by ID.
- POST /posts - Create a new post.
- PATCH /posts/:id - Update an existing post by ID.
- DELETE /posts/:id - Delete a post by ID.

## Troubleshooting

- Ensure that both servers are running and listening on their designated ports.
- Check that the API server is accessible from the frontend server.
- Review error messages in the terminal and browser console for debugging.
