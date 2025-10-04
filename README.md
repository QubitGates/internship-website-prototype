# 🌐 Integrated Internship & Placement Portal

## Project Summary
This is a high-fidelity internship management portal built from my first hackathon idea. I couldn't attend the hackathon due to health reasons, but I continued to develop the idea into a full prototype, which was iteratively improved and refined using **Gemini AI and other external tools**.

The portal unifies students, mentors, and placement cell coordinators onto a single platform.

* **Real-time:** Stores and syncs data instantly using **Firebase**.
* **AI-Powered:** Generates resumes, cover letters, and job descriptions using **Google Generative AI Studio**.
* **Live Demo:** [https://internship-website-prototype.web.app/](https://internship-website-prototype.web.app/)

### 🟢 Project Status
**Status:** Prototype Complete (Functional MVP)  
**Deployed:** October 5, 2025

---

## Core Functionality
This table shows the key functionality for each user role and highlights the core technology used to achieve it.

| Dashboard | What it Does | Technology / Feature |
| :--- | :--- | :--- |
| **Student** | Profile Setup (Name, Roll No., CGPA) | **Firebase** Data Sync |
| | **AI Internship Recommendations** | AI-Powered |
| | Work/Project Submissions | **Real-time** Updates |
| | Cover Letter Generator | AI-Powered + **TTS** (Text-to-Speech) |
| | Resume Builder | AI-Powered + **TTS** (Text-to-Speech) |
| **Placement Cell**| Post and Manage Opportunities | **Firebase** Data Sync |
| | **Automatic Student Recommendations** | AI-Powered |
| | Analytics & Progress Charts | **D3.js** Visualization |
| | **AI Job Description Generator** | AI-Powered |
| | Real-time Announcements | **Real-time** Updates |
| **Mentor** | Review Student Profiles | **Real-time** Data Sync |
| | Give Feedback on Submissions | **Real-time** Updates |
| | Track Student Submission Trends | **Real-time** Updates |

---

## Technical Rationale (Architectural Decisions)
As a student project, the goal was to build a modern, high-performance web application. I chose these specific tools to gain hands-on experience with production-level architecture:

1.  **Firebase Firestore:** I used this primarily to learn about **real-time data synchronization**. It ensures any action (e.g., a new announcement) updates instantly across all open dashboards without needing a page refresh.
2.  **Google Generative AI API:** I integrated this to explore **prompt engineering** and make the application truly helpful by creating the resume/cover letter tools.
3.  **D3.js:** I selected D3.js specifically for the Student Progress Tracker to gain experience with a powerful JavaScript library for **complex data visualization**.
4.  **Styling:** I combined the rapid utility-first nature of **Tailwind CSS** with custom inline CSS to practice advanced UI effects like **glassmorphism** and the **glowing button** animation.

---

## Technology Stack
* **Frontend:** HTML, Vanilla JS
* **Styling:** Tailwind CSS (CDN), Custom CSS
* **Charts:** D3.js
* **Icons/Fonts:** Font Awesome 6.5.2, Google Fonts (Inter)
* **Backend:** Firebase Authentication + Firestore (Real-time data), Firebase Hosting
* **AI:** Google Generative AI + **Gemini AI** (for iterative development and core features)

---

## Getting Started (Local Setup)

### Prerequisites
* Node.js & npm
* Firebase CLI:
```bash
npm install -g firebase-tools
```

### Run Locally
```bash
firebase emulators:start
```
Then open `http://localhost:5000` in your browser.

### Deploy to Firebase
```bash
git add .
git commit -m "Describe your changes"
git push origin main
firebase deploy
```

---

## Future Scope & Enhancements
* AI skill gap analysis for students
* Real-time mentor-student chat
* Automated internship matching with external job portals
* Better analytics and charts

---

## 💡 Note
This project started from my first hackathon idea and became a real prototype that works with real-time Firebase data, thanks to iterative development guided by AI tools (Gemini AI was the primary assistant, with other external tools used for troubleshooting).
