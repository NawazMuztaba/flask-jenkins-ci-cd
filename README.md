# Flask CI/CD Pipeline using Jenkins and Docker

This project demonstrates a complete CI/CD pipeline for a Flask application using **Jenkins** and **Docker** on a Linux environment.

The pipeline automatically builds a Docker image, stops any existing container, and deploys the updated Flask application.

---

## 🚀 Tech Stack

- **Python (Flask)**
- **Docker**
- **Jenkins**
- **Git & GitHub**
- **Linux (Kali Linux)**

---

## 📂 Project Structure

flask-jenkins-ci-cd/
├── app/
│ ├── app.py
│ └── requirements.txt
├── Dockerfile
├── Jenkinsfile
└── README.md

---

## ⚙️ CI/CD Workflow

1. Developer pushes code to GitHub
2. Jenkins job is triggered
3. Jenkins performs the following steps:
   - Stops and removes old Docker container (if exists)
   - Builds a new Docker image
   - Runs a new Docker container
4. Flask application is deployed automatically

---

## 🧪 Application Output

After successful deployment, the application is available at:

http://localhost:5000

lua
Copy code

Expected output:
Hello! This app is deployed using Jenkins CI/CD

---

## 🛠 Jenkins Pipeline Stages

- Cleanup old container
- Build Docker image
- Run Flask container

Pipeline is defined using a **Declarative Jenkinsfile**.

---

## 📌 Key Learnings

- CI/CD automation using Jenkins
- Docker image creation and container management
- Jenkinsfile scripting
- End-to-end DevOps workflow
- GitHub integration with Jenkins

---

## 👤 Author

**Nawaz Muztaba**  
GitHub: https://github.com/NawazMuztaba

---

## ✅ Status

✔ Project completed  
✔ CI/CD pipeline working successfully  
✔ Ready for resume and LinkedIn
<img width="2453" height="1338" alt="image" src="https://github.com/user-attachments/assets/0bdd4318-fa1c-4f1b-b189-a339080c600f" />
<img width="2447" height="500" alt="image" src="https://github.com/user-attachments/assets/c8a3c756-b048-48af-b399-fc07fd3a2e22" />
<img width="2445" height="869" alt="image" src="https://github.com/user-attachments/assets/90f0d14d-33c5-45d3-a621-073cb61e4436" />
<img width="2452" height="1398" alt="image" src="https://github.com/user-attachments/assets/f7ecb5b9-3fc8-49b6-a709-4e2ad3e576dc" />




