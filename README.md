# Digital Expense Monitoring and Budget Analysis System

## Project Overview
The Digital Expense Monitoring and Budget Analysis System is a web-based application designed to help users track their daily expenses, manage budgets, and analyze their spending patterns. The system provides a simple and user-friendly interface for recording expenses and generating financial insights.

---

## Problem Statement
Many individuals, especially students, struggle to manage their daily expenses and budgets. Traditional methods like notebooks or spreadsheets are inefficient and error-prone. Existing applications are often complex or expensive. This system aims to provide a simple and accessible solution for expense tracking and budget analysis.

---

## Target Users (Personas)

### 1. Student
- Age: 18–25  
- Needs to track daily expenses  
- Wants to manage limited budget  

### 2. Young Professional
- Wants to monitor monthly spending  
- Needs insights into financial habits  

---

## Vision Statement
To provide a simple, efficient, and user-friendly digital platform that enables users to track expenses, manage budgets, and make better financial decisions.

---

## Key Features / Goals
- Add, edit, and delete expenses  
- Categorize expenses (food, travel, etc.)  
- Set monthly budgets  
- Generate expense reports  
- Show alerts when budget is exceeded  
- Provide simple and clean user interface  

---

## Success Metrics
- Users can easily add and manage expenses  
- Accurate tracking of expenses and budgets  
- Users can understand their spending patterns  
- At least 80% of users can use the system without help  

---

## Assumptions
- Users have access to internet and browser  
- Users will manually enter expense data  
- Basic technical knowledge is sufficient  

---

## Constraints
- Developed within limited academic timeline  
- Uses free and open-source tools  
- Simple UI design for ease of use  
## Quick Start – Local Development

### Steps to Run

1. Build Docker Image  
docker build -t expense-app .

2. Run Container  
docker run -p 8080:80 expense-app

3. Open in Browser  
http://localhost:8080

## Software Design

The system follows a layered client-server architecture ensuring modularity and scalability. The UI is designed using simple and consistent layouts to improve usability.

### Architecture Diagram
![Architecture](docs/design/architecture.png)

### UI Wireframes
![Figma](docs/design/figma.png)
