# To Do List Web Application

This is a simple web application built with Node.js and Express for managing personal tasks and goals.

## Prerequisites

Make sure you have the following installed on your machine:

- Node.js (LTS version)
- npm (Node Package Manager)

## Getting Started

Follow these steps to get the project up and running on your local machine:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/ErickNani/myapp.git
    ```

2. Navigate to the project directory:

    ```bash
    cd your-repository
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Set up your API key:

    - In the root directory, create a file named `.env`.
    - Inside `.env`, add the following line:

        ```
        API_KEY=123456
        ```

    Replace `123456` with your actual API key.

5. Start the server:

    ```bash
    npm start
    ```

6. Open your web browser and navigate to `http://localhost:3000` to access the application.

## Endpoints

- `GET /getTasks`: Retrieve all tasks.
- `GET /getGoals`: Retrieve all goals.
- `DELETE /removeTask/:id`: Remove a task.
- `DELETE /removeGoal/:id`: Remove a goal.
- `POST /addTask`: Add a new task.
- `POST /addGoal`: Add a new goal.

## Middleware

- The backend includes a middleware that checks for the presence of an `Authorization` header with the value `123456`.

## Note

- Data is not persisted and will be reset upon server restart.

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
