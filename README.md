# 🧭 PathMate — Your Digital Campus Companion

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Google Gemini" />
</p>

**PathMate** is an AI-powered digital campus companion designed for freshers at **Saranathan College of Engineering (SCE)**. It brings campus navigation, academic resources, student communities, onboarding tools, and college information into one platform—helping students settle into campus life with greater confidence.

Instead of searching across multiple sources, students can use PathMate to navigate campus, discover opportunities, manage tasks, access learning resources, and get assistance through an AI-powered campus companion.

## ✨ Key Features

### 🗺️ Interactive Campus Navigation
- Explore campus using **satellite and 2D map views**.
- Discover buildings and campus locations through interactive markers.
- Navigate with walking routes and entrance selection.
- Track your position using GPS and recalculate routes when needed.

### 🤖 AI-Powered Campus Assistant
- Get assistance with college information and campus-related questions.
- Access academic guidance and student support through a conversational interface.
- Integrate the Gemini API with a database-first approach to prioritize available college information.

### 🎓 Academic Hub
- Access study materials and academic resources.
- Follow onboarding checklists to get started with college life.
- Organize tasks and keep track of important activities.

### 🤝 Student Community
- Discover clubs and campus events.
- Connect with senior mentors.
- Explore roommate discovery features.
- Find relevant hostel and transport information.

### 📢 Campus Updates
- Access official notices and important announcements.
- Stay informed about college activities and events.

### 🛠️ Admin Control Center
- Manage student information and campus content.
- Maintain notices, events, clubs, and campus locations.
- Handle student reviews and support tickets.
- Manage database-backed content through a centralized interface.

## 🧰 Tech Stack

| Technology | Purpose |
|---|---|
| React.js | Interactive frontend |
| Tailwind CSS | Responsive UI styling |
| Node.js | Backend JavaScript runtime |
| Express.js | Backend services and REST APIs |
| PostgreSQL | Relational data storage |
| Firebase | Supporting application integration |
| Gemini API | AI-powered campus assistance |

## 🏗️ High-Level Architecture

```text
              STUDENT / ADMIN
                     |
                     v
             React.js Frontend
              + Tailwind CSS
                     |
                     v
             Express.js REST API
                     |
             +-------+-------+
             |               |
             v               v
         PostgreSQL      Gemini API
         Campus Data     AI Assistance
             |
             v
      Managed Campus Content

        Firebase Integration
```

*Conceptual overview of the main technologies; exact service boundaries depend on the implementation.*

## 🎯 The Problem PathMate Solves

Starting college can be overwhelming. Freshers often need to find unfamiliar buildings, locate academic resources, understand campus procedures, discover student communities, and identify reliable sources of information.

PathMate brings these experiences together in one student-focused digital platform, combining campus navigation, academic support, community discovery, and administrative tools.

## 🚀 Getting Started

To run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/theoudar03/PathMate.git
   cd PathMate
   ```

2. **Install dependencies**  
   Check the repository structure and install dependencies in the relevant frontend and backend directories using `npm install`.

3. **Configure environment variables**  
   Set up the required database connection, Firebase configuration, Gemini API key, and any other environment variables used by the application. Keep secret keys out of source control.

4. **Start the application**  
   Use the development scripts defined in the respective `package.json` files to start the frontend and backend services.

> **Note:** Exact directory names, environment variable names, and run commands should match the current repository implementation.

## 🔐 Security & Responsible Use

- Keep API keys and database credentials in environment variables.
- Restrict administrative functionality to authorized users.
- Handle student information and location data responsibly.
- Treat AI-generated responses as assistance, and verify important college information against reliable sources.

## 🌱 Project Vision

PathMate aims to make the transition into college life more accessible by connecting **navigation, knowledge, student communities, and campus services** in one digital companion.

## 👨‍💻 Developer

**Theoudar Doss D**

- GitHub: [@theoudar03](https://github.com/theoudar03)
- LinkedIn: [Connect on LinkedIn](https://www.linkedin.com/in/theoudar/)

---

<p align="center">
  <strong>Find your way. Find your people. Make campus feel like home. 🧭</strong>
</p>
