# AI Workflow Assistant

An AI-powered web app that helps teams design, run, and track **multi-step workflows** from plain-language descriptions.  
Built as a startup-style MVP to showcase **AI integration, full-stack development, and cloud deployment** skills.

![screenshot](docs/screenshot.png) <!-- optional image -->

---

## 🚀 Features

- **Natural Language to Workflow**  
  Type a description like _"Onboard a new software engineer"_ and the app generates suggested workflow steps using an AI model (OpenAI GPT).

- **Multi-Step Workflow Execution**  
  Store and run workflows composed of manual, AI-generated, or API steps. Tasks are tracked with statuses (`pending → running → done`).

- **Progress Tracking**  
  Each workflow shows its steps in order with live updates and an activity log.

- **Cloud-Ready Architecture**  
  Backend + frontend are containerized with Docker and deployable to platforms like Fly.io, Render, or Heroku.

---

## 🛠 Tech Stack

- **Frontend:** [React](https://react.dev/) + Vite, [React Router](https://reactrouter.com/), [TanStack Query](https://tanstack.com/query)  
- **Backend:** [FastAPI](https://fastapi.tiangolo.com/) (Python 3.12)  
- **Database:** [PostgreSQL](https://www.postgresql.org/) with JSONB for flexible step configs  
- **AI Integration:** [OpenAI API](https://platform.openai.com/) (GPT models for workflow generation)  
- **DevOps:** Docker & Docker Compose, GitHub Actions CI/CD  
- **Optional Extensions:** Redis for background jobs, Fly.io/Render deployment

---

## 📂 Project Structure

