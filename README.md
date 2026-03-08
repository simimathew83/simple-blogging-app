# Simple Blogging App (Full-Stack Project)

A **full-stack blogging application** built with:

- **Frontend:** React + Vite  
- **Backend:** Spring Boot + PostgreSQL  

This project demonstrates a fully deployed application with **separate frontend and backend services on Render**.

---

## Live Demo

- **Frontend:** [https://simple-blogging-app-frontend.onrender.com](https://simple-blogging-app-frontend.onrender.com)  
- **Backend API:** [https://simple-blogging-app-backend.onrender.com](https://simple-blogging-app-backend.onrender.com)  

> Both frontend and backend are hosted on **Render**, communicating via environment-variable-configured URLs. Users can access the full app directly without any setup.

---

## Repositories

- **Frontend code:** [simple-blogging-app-frontend](https://github.com/simimathew83/simple-blogging-app-frontend)  
- **Backend code:** [simple-blogging-app-backend](https://github.com/simimathew83/simple-blogging-app-backend)  

> These two repos contain the actual code for the project. This repo serves as an overview and documentation.

---

## Features

- Create, view, search, and delete blog posts  
- Fully responsive UI  
- REST API backend with PostgreSQL database  
- Environment-variable-based configuration for backend URL and database credentials  

---

## Running Locally

If you want to run the project locally:

1. **Clone frontend and backend repos**:

```bash
git clone https://github.com/simimathew83/simple-blogging-app-backend
git clone https://github.com/simimathew83/simple-blogging-app-frontend
```
2. **Backend (Spring Boot)**

- Create a `.env` or update `application.properties` with your local PostgreSQL credentials.

- Run backend:
```
./gradlew bootRun
```
3. **Frontend (React + Vite)**

- Create .env.local with:
```
VITE_BACKEND_URL=http://localhost:8080
```
- Install dependencies and start frontend:
```
npm install
npm run dev
```
Local environment variables are only needed for development. The deployed app on Render works out-of-the-box.

---

## Notes:
- CORS is configured to allow requests from localhost for development and the deployed frontend on Render.
- Database credentials are managed securely via Render environment variables — no sensitive info is exposed.
- This repo provides an overview for portfolio purposes and links to the actual code.

---

## License
Open-source and free to use.
