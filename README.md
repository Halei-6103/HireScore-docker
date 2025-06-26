# 🧠 Programmer Prep Checklist Projects

This repo contains two beginner-friendly Docker-based projects designed to strengthen your developer workflow and Docker fundamentals. Each project is zipped separately and includes everything needed to get started.

## 📦 Included Projects

---

### ✅ 1. **To-Do App (Node.js + MySQL)**

- **Source:** Docker's official assessment project
- **Purpose:** Practice multi-container setup with Docker Compose
- **Stack:** Node.js + MySQL
- **Docker Features Used:** Networks, volumes, environment variables, Compose

#### 💻 How to Run:

1. **Unzip `todo-app.zip`**
2. Open a terminal in the unzipped folder
3. Run the following command:

```bash
docker compose up -d
```
4. Open your browser and go to:

```bash
http://localhost:3000
```
5. When you're done, stop the containers:

```bash
docker compose down
```
### 👋 2.Hello HireScore (PHP + Dockerfile)

This project is based on a FreeCodeCamp tutorial and demonstrates a basic PHP web app that prints "Hello HireScore" in the browser. It showcases how to build and run a Docker container using a custom Dockerfile.

**Purpose**: Understand Dockerfiles and building images manually.

**Stack**:
- PHP
- Custom Dockerfile

**How to Run**:
1. Unzip `hello-hirescore.zip`  
2. Open a terminal in the unzipped folder  
3. Build the image:

```bash
docker build -t hello-hirescore .
```
4. Run the container:

```bash
docker run -d -p 8080:80 hello-hirescore
```
5. Open your browser and go to:

```bash
http://localhost:8080
```
6. To stop the container:

```bash
docker ps    # find the container ID
docker stop <container-id>
```
