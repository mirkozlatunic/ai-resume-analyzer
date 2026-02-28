## AI Resume Analyzer

![Home page where the “Upload resume” text is shown](public/images/Screenshot%202026-02-28%20at%2011.02.50%E2%80%AFAM.png)

![Resume review page](public/images/Screenshot%202026-02-28%20at%2011.03.02%E2%80%AFAM.png)

**AI-powered resume analyzer that scores your CV, simulates ATS checks, and delivers job-specific feedback so you can track applications and improve faster.**

Live demo: [`ai-resume-analyzer on puter.com`](https://puter.com/app/zlm-ai-resume-analyzer)

---

### Overview

This project is a full-stack React application that helps job seekers:

- **Analyze** their resume content with AI
- **Simulate ATS checks** (keyword matching and structure)
- **Score resumes** based on role-specific criteria
- **Get actionable feedback** on how to improve
- **Track applications** and compare resume versions over time

It is designed to be a **portfolio-quality project** to demonstrate modern frontend engineering, TypeScript, routing, and clean UI work.

---

### Features

- **AI-powered analysis**
  - Extracts key information (experience, skills, education)
  - Highlights gaps and missing keywords based on target roles
  - Generates improvement suggestions in natural language

- **ATS-style checks**
  - Looks at formatting, headings, and structure
  - Estimates keyword match between resume and target job description

- **Application tracking**
  - Save and view multiple resumes
  - Compare scores and feedback across applications

- **Modern frontend stack**
  - React Router app with data loading and mutations
  - TypeScript-first setup
  - Tailwind CSS styling

---

### Tech Stack

- **Framework**: React Router (full-stack template)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Build tool**: Vite
- **Containerization**: Docker (optional)

---

### Getting Started

#### Prerequisites

- Node.js (LTS recommended)
- npm

#### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/mirkozlatunic/ai-resume-analyzer.git
cd ai-resume-analyzer
npm install
```

#### Development

Run the development server:

```bash
npm run dev
```

The app will be available at `http://localhost:5173`.

#### Production Build

Create an optimized production build:

```bash
npm run build
```

You can then run the built server with:

```bash
npm run start
```

---

### Docker (Optional)

Build and run the app in Docker:

```bash
docker build -t ai-resume-analyzer .

docker run -p 3000:3000 ai-resume-analyzer
```

---

### Project Structure (High Level)

Some key directories:

- `app/` – React Router routes, loaders, actions, and UI components
- `types/` – Shared TypeScript types for resume data and scoring
- `contants/` – Shared constants and configuration

---

### How This Project Showcases My Skills

- **Frontend architecture**: Route-based layout, shared components, and clear separation of concerns.
- **TypeScript usage**: Strong typing for resume data, analysis results, and UI props.
- **Developer experience**: Vite, hot reload, and clean project structure.
- **Product thinking**: Focused on a real-world job search problem with clear user value.

If you’re reviewing this as part of a job application and want to know more about implementation details, feel free to open an issue or reach out. 🙂
