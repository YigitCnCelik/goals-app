# goals-app

This is a full-stack application for managing goals. The backend is built with Node.js, Express, and MongoDB, while the frontend is built with React.

## Project Structure


## Backend

The backend is located in the `backend` directory and is built with Node.js, Express, and MongoDB.

### Setup

1. Navigate to the `backend` directory:

    ```sh
    cd backend
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

3. Create a `.env` file in the `backend` directory with the following content:

    ```env
    MONGODB_USERNAME=<your-mongodb-username>
    MONGODB_PASSWORD=<your-mongodb-password>
    ```

4. Start the backend server:

    ```sh
    npm start
    ```

### Endpoints

- `GET /goals`: Fetch all goals.
- `POST /goals`: Add a new goal.
- `DELETE /goals/:id`: Delete a goal by ID.

## Frontend

The frontend is located in the `frontend` directory and is built with React.

### Setup

1. Navigate to the `frontend` directory:

    ```sh
    cd frontend
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

3. Start the frontend development server:

    ```sh
    npm start
    ```

### Available Scripts

In the `frontend` directory, you can run:

- `npm start`: Runs the app in development mode.
- `npm test`: Launches the test runner.
- `npm run build`: Builds the app for production.
- `npm run eject`: Ejects the Create React App configuration.

## Docker

Both the backend and frontend have Docker support.

### Backend

1. Navigate to the `backend` directory:

    ```sh
    cd backend
    ```

2. Build the Docker image:

    ```sh
    docker build -t goals-backend .
    ```

3. Run the Docker container:

    ```sh
    docker run -p 80:80 goals-backend
    ```

### Frontend

1. Navigate to the `frontend` directory:

    ```sh
    cd frontend
    ```

2. Build the Docker image:

    ```sh
    docker build -t goals-frontend .
    ```

3. Run the Docker container:

    ```sh
    docker run -p 3000:3000 goals-frontend
    ```

## Learn More

- [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started)
- [React documentation](https://reactjs.org/)
- [Express documentation](https://expressjs.com/)
- [Mongoose documentation](https://mongoosejs.com/)

## License

This project is licensed under the MIT License.