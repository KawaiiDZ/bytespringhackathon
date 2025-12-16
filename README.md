# Awkum Web Hackathon Project

## Course Project Submission

**Student Name:** Muhammad Ali  
**Program:** BS Computer Science – Software Engineering (CS-SW)  
**Batch:** Class of 2027  
**Year:** 2025  
**Institution:** Abdul Wali Khan University, Mardan (AWKUM)

---

## 📘 Project Overview

The **Awkum Web Hackathon Project** is a frontend web application developed as an academic submission. The project demonstrates practical implementation of modern web development concepts using a component-based architecture and responsive design principles.

This submission reflects the application of theoretical coursework into a functional and deployable web solution.

---

## 🎯 Objectives

- Develop a responsive and user-friendly web application  
- Apply component-based frontend architecture  
- Demonstrate proficiency in React and Gatsby  
- Maintain clean, modular, and well-documented code  
- Produce a project suitable for academic evaluation  

---

## 🛠 Technologies Used

- **React.js**
- **Gatsby.js**
- **JavaScript (ES6+)**
- **HTML5 & CSS3**
- **Node.js & npm**

---

## 💻 System Requirements

- Node.js (Latest LTS recommended)
- npm (Node Package Manager)
- Modern web browser

---

## 📂 Project Structure

Awkum-Web-Hackathon-Project/
│
├── public/ # Static assets and build output
├── src/ # Application source code
│ ├── Components/ # Reusable UI components
│ ├── Pages/ # Page-level components
│ ├── layouts/ # Layouts and sections
│ ├── data/ # Structured project data
│ └── App.js # Routing and navigation
│
├── Documentation/ # Supporting documentation
└── package.json # Project dependencies

yaml
Copy code

---

## 🚀 Installation & Execution

### Run Locally (Development)

bash
npm install
npm run start
Build for Deployment
bash
Copy code
npm run build
This generates a production-ready build folder.

⚙️ Customization Guide
Navigation & Routing
Managed in:

css
Copy code
src/App.js
Component Management
Homepage sections:

css
Copy code
src/Components/Home/Home.jsx
Components can be rearranged or replaced as needed.

Create a New Section
Go to:

bash
Copy code
src/Components/layouts/
Create a new .jsx file

Export the component

Import it into Home.jsx

Create a New Page
Create a page in:

css
Copy code
src/Components/Pages/
Export the page component

Register the route in App.js

Link it via the navigation menu

📩 Contact Form Configuration
Form location:

css
Copy code
src/Components/layouts/Contact/Form.jsx
Email configuration:

Copy code
email.js
Update the following:

Service ID

Template ID

Public Key

Note: Do not modify templateParams.

🎨 Styling & Design
Global Styles
swift
Copy code
public/assets/css/style.css
Global colors and themes can be customized from this file.

📜 Academic Declaration
This project has been developed independently by the student for academic submission. All external libraries and tools are used in accordance with their respective licenses.

📄 License
pgsql
Copy code
© 2025 Muhammad Ali
BS Computer Science – Software Engineering (CS-SW)
Class of 2027

All rights reserved.

This project is submitted for academic evaluation only.
Unauthorized reproduction, redistribution, or commercial use
without prior written permission is strictly prohibited.
