# CareerAI

CareerAI is an AI-powered career co-pilot designed to help software engineers optimize their resumes, analyze job descriptions, and track their applications.

## 🏗 Architecture Summary

CareerAI is built as a TypeScript monorepo to ensure type safety across the entire stack.

- **Frontend:** React + Vite (Single Page Application)
- **Backend:** NestJS (Modular Enterprise Framework)
- **Shared:** A common package for Zod schemas and TypeScript types
- **Database:** PostgreSQL with Prisma ORM
- **AI:** Provider-agnostic architecture (starting with Ollama)

## 📁 Repository Structure

```text
career-ai/
├── apps/
│   ├── web/                 # React frontend
│   └── api/                 # NestJS backend
├── packages/
│   └── shared/              # Shared types and Zod schemas
├── docker/                  # Infrastructure configs
└── .github/workflows/        # CI/CD pipelines
```

## 🛠 Development Prerequisites

- **Node.js:** v20+
- **npm:** v10+
- **Git**
- **Ollama** (for local AI analysis)

## 🚀 Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd career-ai
   ```

2. Install all dependencies:
   ```bash
   npm install
   ```

### Running the Application

To start both the frontend and backend in development mode:
```bash
npm run dev
```

- **Frontend:** http://localhost:5173
- **Backend:** http://localhost:3000
