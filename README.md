# Project management system using MERN stack

This project is a project management system built using the MERN stack (MongoDB, Express, React, Node.js) and styled with Tailwind CSS. It allows users to manage projects, track tasks, and collaborate effectively within teams.

---

## Packages used
- Tailwindcss
- Headlessui
- React router
- Axios
- UUID
- Joi
- Cors
- Dotenv

---

## Setup instruction

- Step 1: Install dependencies/node_modules
  - Go to the `/backend` directory for backend setup and run:
    ```bash
    cd /backend
    npm install
    ```

  - Go to the `/frontend` directory for frontend setup and run:
    ```bash
    cd /frontend
    npm install
    ```

- Step 2: Configure MongoDB connection URL
  - Go to the `backend` directory and create a `.env` file, then add the following line:
    ```bash
    MONGODB_PATH=your-mongodb-connection-url
    ```

- Step 3: Change server port and CORS origin (Optional)
  - By default, the server runs on port `http://localhost:9000` and CORS origin/frontend URL is `http://localhost:3000`. You can change the port and CORS origin by adding the following keys in your `.env` file:
    ```bash
    SERVER_PORT=your-port
    CORS_ORIGIN=your-client-origin
    ```

- Step 4: Run the project
  - In your backend, run the following command to start the Node server:
    ```bash
    node server.js
    ```

  - In your frontend, run the following command to start the React app:
    ```bash
    npm run start
    ```

---

## Project Screenshot
#### Todo board quick preview
![React-App](https://user-images.githubusercontent.com/96901635/191009449-0083044c-c961-45cd-9da4-7184289b9573.gif)
#### Todo board
![image](https://user-images.githubusercontent.com/96901635/191006996-0c185cdd-5834-47c6-8927-2e7d539866a7.png)
#### Task insert
![image](https://user-images.githubusercontent.com/96901635/191007092-eb25cfc8-c056-4be2-a898-00ad29d65785.png)
#### Edit task
![image](https://user-images.githubusercontent.com/96901635/191008217-6a0175e6-d5a9-4d98-8951-4a528d2bef99.png)
#### Edit project
![image](https://user-images.githubusercontent.com/96901635/191008043-8c9113a1-700f-42bb-9f87-e68db159c4dc.png)


---

## Contributions

Contributions are welcome! Feel free to fork the repository and submit a pull request.

