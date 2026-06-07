# Assignment IV – Deploy Your First Web App using GitHub & Render

## Student Information

* **Name:** Sangay Kenchap
* **Student ID:** 02250366
* **Module:** DSO101 – Continuous Integration and Continuous Deployment

---

## Project Description

This project demonstrates the creation of a simple static web application and its integration with GitHub. A GitHub Actions workflow was configured to run automatically whenever changes are pushed to the main branch.

The web application contains a simple user interface with a button that displays a message, demonstrating basic HTML, CSS, and JavaScript functionality.

---

## Technologies Used

* HTML
* CSS
* JavaScript
* Git
* GitHub
* GitHub Actions
* Render

---

## Project Structure

```text
.
├── index.html
├── style.css
├── .github
│   └── workflows
│       └── deploy.yml
└── README.md
```

---

## Features

* Simple responsive web page
* Interactive button using JavaScript
* Version control using Git and GitHub
* Automated workflow execution using GitHub Actions

---

## Implementation Steps

### 1. Create the Web Application

A basic web application was developed using HTML and CSS. JavaScript was added to display a success message when the button is clicked.

### 2. Git Repository Setup

* Initialized a Git repository.
* Added project files.
* Committed changes.
* Pushed the project to GitHub.

### 3. GitHub Actions Workflow

A workflow was created in:

```text
.github/workflows/deploy.yml
```

The workflow is triggered whenever code is pushed to the `main` branch.

### 4. Render Deployment

The GitHub repository was connected to Render for hosting the web application. Any updates pushed to GitHub can be synchronized with the Render deployment configuration.

---

## Screenshots Included

1. GitHub Repository
2. GitHub Actions Workflow
3. Render Dashboard
4. Running Web Application

---

## Learning Outcomes

Through this assignment, I learned:

* How to use Git for version control.
* How to host source code on GitHub.
* How GitHub Actions workflows are configured and triggered.
* Basic concepts of Continuous Integration and Continuous Deployment (CI/CD).
* How cloud hosting platforms such as Render can be connected to GitHub projects.

---

## Project Links

### GitHub Repository

https://github.com/Sangay-Kenchap/SangayKenchap_02250366_DSO101_A4

### Live Application

https://sangaykenchap-02250366-dso101-a4.onrender.com

---

## Conclusion

This assignment provided practical experience with modern DevOps tools and workflows. By integrating GitHub, GitHub Actions, and Render, the project demonstrated the foundational concepts of Continuous Integration and Continuous Deployment while deploying a simple web application.