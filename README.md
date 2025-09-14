
# 📘 LearnHub: Your Centre for Skill Enhancement

LearnHub is an education-based web platform developed as a mini project to help students learn programming languages and technical courses through a centralized system. The platform is designed for **skill centers** where students can enroll, access interactive learning modules, and track their progress.

🔗 **Live Demo:** [LearnHub on Render](https://learnhub-frontend-4dsc.onrender.com/)

---

## 🚀 Project Overview

### 🎯 Objective
To build an online learning system for students to access and learn courses like **Python, Java, HTML, React, Django**, and more.

### ✨ Features
- 📝 Course browsing and enrollment  
- 🎓 Student login & progress tracking  
- 📊 Interactive dashboards  
- 📱 Responsive and modern UI  
- 👤 Profile management  
- 🔐 Role-based access (Student / Instructor / Admin)  

---

## 🛠️ Technology Stack
- **Frontend:** React.js  
- **Backend:** Node.js / Express.js *(if used)*  
- **Database:** MongoDB / Firebase *(if used)*  
- **Hosting:** Render  

---

## 📸 Screenshots & Pages

### 🏠 Home Page

<img width="350" height="300" alt="image" src="https://github.com/user-attachments/assets/e83509c5-a9dd-4546-909c-91187c629012" />

- Welcomes users with tagline **“Level Up Your Skills”**.  
- Navigation: Home, Dashboard, Courses, My Courses, Profile, Logout.  

### 🔐 Authentication
- **Signup Page:** New users can register as *Student* or *Instructor*.

- <img width="350" height="300" alt="image" src="https://github.com/user-attachments/assets/0efc1a9e-8e25-4808-8f28-61a916381276" />
 
- **Login Page:** Returning users can log in securely.  

### 🎓 Student Dashboard
<img width="350" height="300" alt="image" src="https://github.com/user-attachments/assets/b5f35b12-3514-429b-8184-223cafcd46fe" />

- Personalized greeting.  
- Quick access to **Browse Courses** and **Enrolled Courses**.  

### 📚 My Courses
- Displays all enrolled courses with details and comments.  

### 👤 Profile Page
<img width="350" height="300" alt="image" src="https://github.com/user-attachments/assets/1df3bb06-3287-49b9-94b7-85342b0369dc" />

- Shows user details, role, and enrolled courses.  

### 📚 All Courses
<img width="350" height="300" alt="image" src="https://github.com/user-attachments/assets/a91f740b-42fe-4c50-acc1-8bfff7baecec" />

- Browse all available courses.  
- Filter by category.  
- Options to Buy / Enroll.  
- Add & view course comments.  

### 🧑‍💼 Admin Dashboard

<img width="350" height="300" alt="image" src="https://github.com/user-attachments/assets/e3c0ac44-e452-4be0-b25d-28f788da0f64" />

- View users and roles.  
- Monitor total users and courses.  
- Manage platform effectively.  

---

## 🏗️ System Architecture

### ER Diagram
- **User, Course, Enrollment, Lesson, Feedback** entities.  
- Relationships mapped for student enrollment and feedback.  

### Data Flow Diagram
- **Level 0:** Student ↔ LearnHub System ↔ User DB / Course DB  
- **Level 1:** User Management, Enrollment Management, Course Management  

---

## ⚙️ Installation & Setup

### ✅ Prerequisites
- Node.js  
- React environment (`create-react-app` or Vite)  
- MongoDB (if using database)  
- VS Code (recommended)  
- Internet connection  

### 🔧 Setup Instructions
```bash
# Clone frontend repo
git clone https://github.com/yourusername/learnhub-frontend

# Move into project folder
cd learnhub-frontend

# Install dependencies
npm install

# Start the app
npm start
````

## 📈 Future Scope

* Add quizzes and assessments
* Certificate generation for completed courses
* Advanced admin panel for course management
* Chat-based doubt resolution
---

Do you want me to also add the **screenshots with image tags (`![alt text](url)`)** inside the README so that GitHub displays the actual UI images?
```
