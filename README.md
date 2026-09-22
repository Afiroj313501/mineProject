# mineProject
This # ResearchPilot AI

> AI-powered research assistant for semantic document retrieval, citation-grounded question answering, and research paper analysis.

**ResearchPilot AI** is a full-stack AI research assistant that allows users to upload research papers, organize them into collections, and ask natural-language questions about their documents.

The system uses **Retrieval-Augmented Generation (RAG)** to retrieve semantically relevant document chunks before generating answers, helping keep responses grounded in the user's uploaded research materials.

## 🚀 Live Demo

**Live Application:** https://research-pilot-orcin.vercel.app

**Repository:** https://github.com/Afiroj313501/ResearchPilot

## ✨ Features

* 🔐 JWT-based authentication
* 📚 Research collection management
* 📄 PDF document upload
* 📝 Automatic PDF text extraction
* ✂️ Document chunking
* 🧠 Semantic embeddings
* 🔎 Vector similarity search
* 🤖 Gemini-powered question answering
* 📌 Source-aware responses
* 🔗 Citation/reference information
* 💬 Research document Q&A
* 🗄️ PostgreSQL + pgvector storage
* ⚡ RESTful backend API
* 🔒 Protected API routes

## 🧠 RAG Pipeline

```text
PDF Upload
    ↓
Text Extraction
    ↓
Document Chunking
    ↓
Gemini Embeddings
    ↓
PostgreSQL + pgvector
    ↓
User Question
    ↓
Query Embedding
    ↓
Vector Similarity Search
    ↓
Relevant Chunks
    ↓
Gemini LLM
    ↓
Grounded Answer + Sources
```

## 🛠️ Tech Stack

### Frontend

* React
* Vite
* JavaScript/TypeScript
* React Router
* CSS

### Backend

* Node.js
* Express.js
* TypeScript
* REST API
* JWT Authentication

### Database

* PostgreSQL
* pgvector
* Prisma ORM
* Supabase

### AI

* Google Gemini API
* Gemini Embeddings
* Retrieval-Augmented Generation (RAG)

## 📂 Main Application Modules

```text
Authentication
├── Register
├── Login
└── Protected Sessions

Research Management
├── Collections
├── Documents
└── PDF Processing

AI Research
├── Embeddings
├── Semantic Search
├── RAG
└── Citation-Grounded Answers
```

## ⚙️ Environment Variables

### Backend

```env
PORT=5000
CLIENT_URL=http://localhost:5173

DATABASE_URL=your_postgresql_connection_string

JWT_SECRET=your_jwt_secret

GEMINI_API_KEY=your_gemini_api_key
```

### Frontend

Configure the backend API URL according to your deployment environment.

## 🧑‍💻 Local Development

### Clone

```bash
git clone https://github.com/Afiroj313501/ResearchPilot.git

cd ResearchPilot
```

### Backend

```bash
cd server
npm install
npm run dev
```

### Frontend

```bash
cd client
npm install
npm run dev
```

## 🗄️ Database

ResearchPilot uses PostgreSQL with `pgvector` for storing and searching document embeddings.

The backend uses Prisma with the PostgreSQL adapter for database access.

## 🔐 Security

* JWT-based authentication
* Protected API routes
* Environment-based secret management
* User-specific document access
* Server-side AI API key protection

## 🔮 Future Improvements

* Multi-document conversations
* Advanced citation visualization
* Research paper summarization
* Automatic literature review generation
* PDF page-level citations
* Research methodology extraction
* Paper comparison
* Export conversations
* Research workspace collaboration

## 👨‍💻 Author

**Abdullah Firoj**

GitHub: https://github.com/Afiroj313501
LinkedIn: https://www.linkedin.com/in/abdullah-firoj-900697375/
 my first Git repository all
<br> 
author- Abdullah Firoj

# LumenLearner

> AI-powered Learning Management System with course management, assessments, progress tracking, and an AI/RAG learning assistant.

**LumenLearner** is a full-stack Learning Management System designed to connect students, instructors, and administrators through a centralized educational platform.

The platform supports course creation, multimedia lessons, enrollment, progress tracking, quizzes, assignments, grades, and an AI-powered course assistant.

## 🚀 Live Demo

**Live Application:** https://lumenlearner-iota.vercel.app

**Repository:** https://github.com/Afiroj313501/LumosLearn

## ✨ Features

### 👨‍🎓 Student

* Browse courses
* Enroll in courses
* Watch course lessons
* Access learning materials
* Track course progress
* Take quizzes
* Submit assignments
* View grades
* Ask AI-powered course questions

### 👨‍🏫 Instructor

* Create courses
* Manage course content
* Upload learning materials
* Create quizzes
* Create assignments
* Manage student submissions
* Assign grades
* Monitor student progress

### 🛡️ Administrator

* Manage users
* Manage courses
* Manage platform content
* Monitor the learning ecosystem

### 🤖 AI Learning Assistant

* Course-aware Q&A
* Retrieval-Augmented Generation
* Context-based answers
* Learning material retrieval
* AI-assisted learning support

## 🛠️ Tech Stack

### Frontend

* React
* Vite
* JavaScript/TypeScript

### Backend

* Node.js
* Express.js
* REST APIs
* JWT Authentication

### Database

* PostgreSQL
* Prisma ORM

### AI

* Google Gemini
* Retrieval-Augmented Generation (RAG)

### Learning Content

* YouTube videos
* PDF
* PPTX
* DOCX

## 🏗️ Architecture

```text
React Frontend
       ↓
Express REST API
       ↓
Authentication Layer
       ↓
Business Logic
       ↓
PostgreSQL
       ↓
AI / RAG Layer
       ↓
Gemini
```

## 🔐 Authentication

The application implements role-based authentication for:

```text
ADMIN
INSTRUCTOR
STUDENT
```

JWT tokens are used to protect authenticated resources.

## 📚 Course System

Each course can contain:

* Lessons
* Videos
* Documents
* Quizzes
* Assignments
* Grades
* Progress information

## 🤖 AI + RAG

The AI assistant is designed to answer questions using course-related learning materials instead of relying solely on general model knowledge.

```text
Course Materials
      ↓
Document Processing
      ↓
Embeddings / Retrieval
      ↓
Relevant Context
      ↓
Gemini
      ↓
Course-Aware Answer
```

## ⚙️ Installation

```bash
git clone https://github.com/Afiroj313501/LumosLearn.git

cd LumosLearn
npm install
```

Configure your environment variables and database before starting the application.

## 🔧 Environment Variables

Example:

```env
DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
CLIENT_URL=http://localhost:5173
```

## 🔮 Future Improvements

* Live classes
* Real-time notifications
* Student analytics dashboard
* AI-generated quizzes
* Personalized learning paths
* Course recommendation engine
* Learning performance analytics
* Certificate generation

## 👨‍💻 Author

**Abdullah Firoj**

GitHub: https://github.com/Afiroj313501

# CareerForge AI

> AI-powered career development platform designed to help users build resumes, prepare for interviews, improve coding skills, and plan their careers.

**CareerForge AI** is a planned AI career platform that combines multiple career-development tools into a single application.

## 🎯 Vision

CareerForge AI aims to provide an integrated career workspace where users can:

```text
Build Resume
     ↓
Analyze Resume
     ↓
Improve Skills
     ↓
Practice Interviews
     ↓
Practice Coding
     ↓
Build Portfolio
     ↓
Track Career Progress
```

## ✨ Planned Features

### 📄 AI Resume Builder

* Resume generation
* Resume customization
* ATS-friendly formatting
* Multiple templates
* Job-specific resume adaptation

### 📊 ATS Resume Analyzer

Analyze resumes for:

* Keyword coverage
* Skills
* Formatting
* Job-description alignment
* Missing sections
* Improvement suggestions

### 🎤 AI Interview Coach

* Behavioral interview practice
* Technical questions
* Role-specific interviews
* AI-generated feedback
* Answer improvement suggestions

### 💻 Coding Practice

* Coding problems
* AI hints
* Solution explanations
* Code analysis
* Difficulty-based practice

### 🗺️ Career Roadmap

Generate personalized learning roadmaps covering:

* Programming
* Web development
* AI/ML
* Data
* Cybersecurity
* Cloud
* DevOps

### 🌐 Portfolio Builder

Users can generate and manage:

* Portfolio websites
* Project showcases
* Skills sections
* Experience sections
* Contact information

### 🐙 GitHub Analyzer

Potential analysis includes:

* Repository activity
* Project quality indicators
* Technology usage
* Contribution patterns
* Portfolio recommendations

### 🤖 AI Career Coach

A conversational AI assistant for:

* Career planning
* Skill-gap analysis
* Learning recommendations
* Interview preparation
* Project recommendations

## 🧠 AI Architecture

```text
User Profile
     ↓
Career Goals
     ↓
Resume / GitHub / Skills
     ↓
AI Analysis
     ↓
Career Recommendations
     ↓
Personalized Roadmap
```

## 🛠️ Proposed Tech Stack

### Frontend

* React
* Vite
* Tailwind CSS

### Backend

* Node.js
* Express.js
* TypeScript

### Database

* PostgreSQL
* Prisma

### AI

* Google Gemini API
* RAG
* Embeddings

### Integrations

* GitHub API
* Resume/PDF processing

## 🔐 Security

The platform should implement:

* JWT authentication
* OAuth where appropriate
* Secure API key storage
* User-specific data isolation
* Protected AI endpoints
* Secure file processing

## 📌 Project Status

**Planned / Development Stage**

The feature set may evolve during implementation.

## 🔮 Future Improvements

* Job-board integration
* Automated job matching
* LinkedIn profile analysis
* Application tracking
* Skill progress tracking
* AI-generated study plans
* Mock technical interviews
* Employer dashboards
* Career analytics

## 👨‍💻 Author

**Abdullah Firoj**

GitHub: https://github.com/Afiroj313501

# Extensive Medical Hub

> A full-stack healthcare information and management platform designed to centralize medical resources and services.

**Extensive Medical Hub (IMH)** is a web-based project focused on providing a centralized platform for organizing and accessing healthcare-related information.

## ✨ Features

* Healthcare information management
* Medical resource organization
* User-friendly web interface
* Responsive design
* Structured medical content
* Backend API integration
* Database-backed application architecture

## 🛠️ Tech Stack

* React
* Node.js
* Express.js
* PostgreSQL / Database
* REST API
* JavaScript / TypeScript

## 🏗️ Architecture

```text
React Frontend
      ↓
REST API
      ↓
Express Backend
      ↓
Database
```

## 📂 Project Structure

```text
IMH/
├── client/
├── server/
├── README.md
└── package.json
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Afiroj313501/IMH.git

cd IMH
```

Install dependencies:

```bash
npm install
```

Configure the required environment variables and database connection.

## 🔧 Environment Variables

```env
DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:5173
```

## 🚀 Development

Start the development server according to the project structure.

```bash
npm run dev
```

## 🔮 Future Improvements

* Doctor profiles
* Appointment management
* Patient dashboards
* Medical document management
* Search and filtering
* Health resource recommendations
* Secure user roles
* AI-powered medical information assistant

## ⚠️ Disclaimer

This project is intended for software development and educational purposes. It should not be treated as a substitute for professional medical advice, diagnosis, or treatment.

## 👨‍💻 Author

**Abdullah Firoj**

GitHub: https://github.com/Afiroj313501
