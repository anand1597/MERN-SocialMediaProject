# MERN Social Media Project

A full-stack **Social Media Web Application** built using the **MERN Stack (MongoDB, Express.js, React.js, and Node.js)**.

The project is organized into separate frontend and backend applications and includes Docker configuration for running the application as a containerized setup.

## 🚀 Features

* User registration and authentication
* User login/logout
* Social media style user interface
* Create and manage posts
* View posts from users
* User profiles
* Like and interact with posts
* Backend REST APIs
* MongoDB database integration
* React-based frontend
* Node.js and Express.js backend
* Docker and Docker Compose support
* Nginx configuration for deployment

## 🛠️ Technologies Used

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Axios

### Backend

* Node.js
* Express.js
* REST API
* MongoDB
* Mongoose

### DevOps / Deployment

* Docker
* Docker Compose
* Nginx

## 📁 Project Structure

```text
MERN-SocialMediaProject/
│
├── backend/
│   ├── ...
│   └── ...
│
├── frontend/
│   ├── ...
│   └── ...
│
├── nginx/
│   └── ...
│
├── .gitignore
├── docker-compose.yml
└── README.md
```

## ⚙️ Prerequisites

Make sure you have the following installed:

* Node.js
* npm
* MongoDB
* Git
* Docker (optional)

Check your installations:

```bash
node --version
npm --version
git --version
docker --version
```

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/anand1597/MERN-SocialMediaProject.git
```

Move into the project directory:

```bash
cd MERN-SocialMediaProject
```

## 🔧 Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create your environment file:

```text
.env
```

Add the required environment variables, for example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Start the backend server:

```bash
npm start
```

For development, if the project uses a development script:

```bash
npm run dev
```

## 💻 Frontend Setup

Open another terminal and navigate to the frontend:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the React development server:

```bash
npm start
```

The frontend will normally be available at:

```text
http://localhost:3000
```

The backend will normally run at:

```text
http://localhost:5000
```

> The exact ports and environment variables depend on the configuration in the project.

## 🐳 Running with Docker

This repository includes a `docker-compose.yml` file and an Nginx configuration for containerized deployment.

From the root directory:

```bash
docker compose up --build
```

To run the containers in detached mode:

```bash
docker compose up -d --build
```

To stop the containers:

```bash
docker compose down
```

To view running containers:

```bash
docker compose ps
```

## 🔐 Environment Variables

Do not commit sensitive credentials to GitHub.

Example:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

Make sure `.env` is included in `.gitignore`.

## 🔄 Application Architecture

```text
             ┌──────────────────┐
             │     User         │
             └────────┬─────────┘
                      │
                      ▼
             ┌──────────────────┐
             │ React Frontend   │
             └────────┬─────────┘
                      │
                 HTTP / REST API
                      │
                      ▼
             ┌──────────────────┐
             │ Express / Node   │
             │     Backend      │
             └────────┬─────────┘
                      │
                      ▼
             ┌──────────────────┐
             │     MongoDB      │
             └──────────────────┘
```

For deployment, Nginx can be used as a reverse proxy in front of the application.

## 🧪 Development

To make changes to the project:

```bash
git checkout -b feature/your-feature
```

After making changes:

```bash
git add .
git commit -m "Add your feature"
```

Push the branch:

```bash
git push origin feature/your-feature
```

## 📌 Git Commands

If you want to push changes to your repository:

```bash
git add .
git commit -m "Update project"
git push origin main
```

Repository:

[MERN Social Media Project on GitHub](https://github.com/anand1597/MERN-SocialMediaProject?utm_source=chatgpt.com)

## 📷 Screenshots

Add screenshots of your application here:

```markdown
![Home Page](screenshots/home.png)

![Login Page](screenshots/login.png)

![Profile Page](screenshots/profile.png)
```

## 🔮 Future Improvements

* Real-time chat using Socket.IO
* Notifications
* Follow/unfollow functionality
* Image and video uploads
* Search functionality
* Comments and replies
* Improved authentication and authorization
* Cloud deployment
* CI/CD pipeline
* Unit and integration testing

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your changes
5. Push the branch
6. Create a Pull Request

## 📄 License

This project is intended for educational and development purposes.

## 👨‍💻 Author

**Anand**

GitHub:
[anand1597](https://github.com/anand1597?utm_source=chatgpt.com)
