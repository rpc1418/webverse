# 🌐 Webverse Backend API

This repository contains the backend API for the Webverse application. The API is built using Node.js, Express.js, and Prisma ORM, and is designed to be scalable and easy to maintain. The project also comes with Docker support for containerized deployment.

## 📂 Folder Structure
  ```
  src/                        # Entry folder for the API
    ├── index.js                # Entry point for the application
    ├── router/                 # Folder for route management
    │   ├── router.js           # Main router linking all sub-routes
    │   └── **/exampleRouter.js # Example router linked in the main router
    ├── db.js                   # Global Prisma instance
    env.js                      # Environment variables (export constants from .env)
    Dockerfile                  # Docker configuration to containerize the server
    nodemon.json                # Nodemon configuration for development
    version.txt                 # Environment versions
    prisma/                     # Prisma ORM configuration
        ├── schema.prisma       # Prisma schema file
        └── dev.db              # SQLite database for development
```

## 🚀 Scripts

Here are some useful scripts for running the project:

- `npm run dev`: Run the server in development mode with Nodemon.
- `npm run start`: Run the server in production mode.
- `npx prisma generate`: Generate the Prisma client for database interaction.
- `npx prisma db push`: Push schema changes to the database.

## 🛠️ Technologies Used

- **Node.js**: Backend runtime environment.
- **Express.js**: Web framework for handling routes and requests.
- **Prisma ORM**: Database ORM for easy database operations.
- **SQLite**: Database used in development.
- **Docker**: Containerization for deployment.
- **Nodemon**: Development tool for automatically restarting the server on changes.

## 📄 Environment Setup

Ensure you have a `.env` file in your project root, which contains the necessary environment variables. Use the `env.js` file to export these variables as constants for use throughout the application.

## 🐳 Docker

To run the API inside a Docker container, simply use the provided `Dockerfile`. It ensures all dependencies are installed and the application runs smoothly.


## 🔧 Prisma Setup

Make sure to initialize the Prisma client and push the schema changes to your database.

```bash
npx prisma generate
npx prisma db push
```


## 📜 License

This project is licensed under the MIT License.


## 🔗 Visit My GitHub:

Explore the code and my other projects here: [GitHub - rpc1418](https://github.com/rpc1418)

Check out my portfolio website: [Rudraksh Chourey's Portfolio](https://rpc1418.github.io/portfolio/)
