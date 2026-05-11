# 🚀 TechCrush Portfolio Website (CI/CD Deployed)

A modern, responsive personal portfolio website showcasing web development skills, deployed using a fully automated CI/CD pipeline with GitHub Actions and AWS S3.

## link 👉: http://techcrush-app-2026.s3-website.eu-north-1.amazonaws.com/

## 👨‍💻 About This Project

This project is a **personal portfolio website** built using HTML and CSS to showcase my skills in:

- Frontend Web Development
- Cloud Deployment
- CI/CD Automation
- Git Version Control

It demonstrates a complete DevOps workflow from development to production deployment.

## ⚙️ Key Features

- 📱 Fully responsive design (mobile & desktop)
- 🎨 Clean modern UI with gradient styling
- 🧠 Sections for skills, projects, and contact info
- 🚀 Automated CI/CD pipeline
- ☁️ Cloud hosting via AWS S3
- 🔄 Auto deployment on every push to GitHub

## 🛠️ Tech Stack

- HTML5
- CSS3
- Git & GitHub
- GitHub Actions (CI/CD)
- AWS S3 (Static Hosting)

## 📁 Project Structure

Techcrush_app/
│
├── index.html # Main portfolio page
├── README.md # Project documentation
└── .github/
└── workflows/
└── deploy.yml # CI/CD pipeline

## 📄 CI/CD Workflow (Summary)

```yaml
on:
  push:
    branches:
      - main

GitHub → GitHub Actions → AWS S3 → Live Deployment
