# AI-Resume-Generator

An AI-powered web application that generates professional resumes 
based on user input using Spring AI for dynamic content generation.

## Features
- Generate professional resumes using AI
- Real-time resume data processing
- Clean and user-friendly interface
- Download/Print resume as PDF

## Tech Stack
- **Frontend:** React.js, Tailwind CSS, Vite
- **Backend:** Java, Spring Boot, Spring AI
- **API:** REST APIs
- **Version Control:** Git

## Project Structure
AI-Resume-Generator/
├── resume_frontend/     # React frontend
└── resume-ai-backend/   # Spring Boot backend

## How to Run

### Backend (IntelliJ / Terminal)
1. Open `resume-ai-backend` in IntelliJ IDEA
2. Add your API key in `application.properties`
3. Run the Spring Boot application

### Frontend (VS Code / Terminal)
1. Open `resume_frontend` folder
2. Install dependencies:
npm install
3. Copy `.env.example` to `.env` and fill values
4. Start the app:
npm run dev
5. Open `http://localhost:5173`

## Environment Variables
Create a `.env` file in `resume_frontend/`:
- `VITE_API_URL` - Backend URL (e.g., http://localhost:8080)

Create `application.properties` in backend:
- `spring.ai.openai.api-key` - Your AI API Key

## Decisions Made
- **React + Vite** for fast frontend development
- **Spring Boot** for robust REST API development
- **Spring AI** for easy AI model integration
- **Tailwind CSS** for quick and clean UI styling
   
