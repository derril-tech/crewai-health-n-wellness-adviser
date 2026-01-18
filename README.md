# 🌱 Health & Wellness Advisor Crew
**Powered by CrewAI + OpenAI**

> **Transform your wellness journey with AI. Enter your goal, constraints, and duration—get a personalized multi-week wellness plan designed by a team of specialized AI agents in seconds.** ⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Next.js](https://img.shields.io/badge/Next.js-16-black.svg)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB.svg)](https://react.dev/)
[![CrewAI](https://img.shields.io/badge/CrewAI-Multi_Agent-purple.svg)](https://www.crewai.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-gpt--4.1--mini-green.svg)](https://openai.com/)
[![Railway](https://img.shields.io/badge/Deploy-Railway-blueviolet.svg)](https://railway.app/)
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-black.svg)](https://vercel.com/)

---

## ✨ What It Does

Health & Wellness Advisor Crew is an intelligent wellness planning platform that uses a **multi-agent CrewAI workflow** to:

1. **Understand Your Goal** — Parse wellness objectives, constraints, and duration using GPT-4.1-mini
2. **Orchestrate Specialists** — Coordinate four specialized AI agents working in harmony
3. **Generate Comprehensive Plans** — Create detailed multi-week plans with workouts, meals, habits, and check-ins
4. **Provide Real-Time Updates** — Watch agents work and see your plan come together incrementally

All in a beautiful, responsive interface with smooth state-driven transitions—no page reloads.

---

## 🎯 Core Features

### 🤖 **AI-Powered Multi-Agent System**
- **CrewAI Orchestration** — Four specialized agents collaborate seamlessly
- **OpenAI Integration** — GPT-4.1-mini with fine-tuned prompts for optimal responses
- **Real-Time Plan Generation** — Watch your personalized plan generate incrementally
- **Agent Chat Interface** — Direct conversation with individual agents for personalized advice

### 👥 **Specialized AI Agents**

| Agent | Expertise | Contribution |
|-------|-----------|-------------|
| 🏋️ **Trainer** | Fitness & Exercise | Custom workout schedules with specific exercises, sets, reps, and progressive difficulty |
| 🥗 **Nutritionist** | Meal Planning & Nutrition | Detailed meal plans with portions, macros, and dietary considerations |
| 🧠 **Psychologist** | Mental Wellness & Habits | Habit formation strategies, mindset guidance, and reflection prompts |
| 🤝 **Accountability Buddy** | Consistency & Motivation | Check-in schedules, progress tracking, and supportive encouragement |

### 📊 **Interactive Planning Experience**
- **Multi-Week Plans** — Comprehensive schedules spanning your entire wellness journey
- **Tabbed Interface** — Organized views for Workouts, Nutrition, Mindset & Habits, and Check-ins
- **Progressive Difficulty** — Plans that build week-over-week toward your goal
- **Constraint-Aware** — Adapts to equipment availability, dietary restrictions, and time constraints

### 🎨 **Modern UI/UX**
- **Single-Page Architecture** — Smooth state-driven transitions without page reloads
- **Dark/Light Mode** — Beautiful theme system with system preference support
- **Mobile-First Design** — Fully responsive with 44px+ touch targets and bottom navigation
- **Animated Transitions** — Delightful micro-interactions and smooth state changes
- **Hero Video Backgrounds** — Dynamic video backgrounds that adapt to theme

### 📱 **Enhanced Features**
| Feature | Description |
|---------|-------------|
| 🎯 **Real-Time Updates** | See agents work and plans generate incrementally |
| ✏️ **Interactive Editing** | Drag-and-drop plan adjustments and inline editing |
| 📈 **Progress Visualization** | Charts, streaks, and completion metrics |
| 💬 **Agent Chat** | Direct conversation with individual agents |
| 📤 **Export & Share** | PDF export and shareable plan links |
| 🎭 **Animated Transitions** | Smooth UI state changes and micro-interactions |
| 🎤 **Voice Input** | Voice-controlled goal entry |
| 📊 **Plan Comparison** | Side-by-side comparison of different plans |

---

## 🏗️ Tech Stack

### **Frontend** ⚛️
| Technology | Purpose |
|------------|---------|
| **Next.js 16** | React 19.2 with App Router, Server Components |
| **TypeScript** | Type-safe development with strict mode |
| **Vanilla Extract** | Tokenized design system with light/dark themes |
| **React 19.2** | Latest React features, concurrent rendering |
| **next-themes** | Theme management with system preference |

### **Backend** 🐍
| Technology | Purpose |
|------------|---------|
| **FastAPI** | High-performance async Python API |
| **CrewAI** | Multi-agent AI orchestration framework |
| **OpenAI GPT-4.1-mini** | Intelligent plan generation and agent responses |
| **Pydantic v2** | Data validation and serialization |

### **Data & Cache** 💾
| Technology | Purpose |
|------------|---------|
| **Supabase** | PostgreSQL database with RPC functions |
| **Upstash Redis** | Job queue, caching, and rate limiting |

### **External APIs** 🔌
| API | Purpose |
|-----|---------|
| **OpenAI** | GPT-4.1-mini for plan generation and agent chat |
| **Nutritionix** | Optional nutrition data enrichment |

### **Deployment** 🚀
| Platform | Service |
|----------|---------|
| **Vercel** | Frontend hosting with edge functions |
| **Railway** | Backend API with auto-scaling |

---

## 📖 User Guide

### Getting Started

1. **Enter Your Goal** — Describe your wellness objective (e.g., "Lose 5kg in 12 weeks")
2. **Add Constraints** — Specify equipment, dietary restrictions, or time availability
3. **Set Duration** — Choose how many weeks your plan should span
4. **Generate Plan** — Watch the AI agents collaborate to create your personalized plan
5. **Explore & Customize** — Review workouts, meals, habits, and check-ins across tabs

### Understanding Your Plan

| Section | What It Shows |
|---------|---------------|
| **Workout Plan** | Progressive exercise routines with specific exercises, sets, reps, and rest periods |
| **Nutrition Plan** | Detailed meal suggestions with portions, macros, and meal timing |
| **Mindset & Habits** | Actionable habit formation strategies with implementation tips |
| **Check-in Schedule** | Weekly reflection questions and progress tracking prompts |

### Pro Tips

- **Be specific** with your goal for better plan personalization
- **Include constraints** to get realistic, achievable recommendations
- **Use Agent Chat** to ask follow-up questions and get personalized advice
- **Track Progress** using the dashboard visualization features
- **Export Plans** to PDF for offline reference

---

## 🎨 Design System

The application uses a **tokenized design system** built with Vanilla Extract, featuring:

- **Agent-Based Color Mapping** — Each agent has a distinct color identity
- **Light/Dark Themes** — Seamless theme switching with system preference support
- **Responsive Layouts** — Mobile-first design with 44px+ touch targets
- **Smooth Animations** — Micro-interactions and state transitions
- **Accessibility** — WCAG-compliant contrast ratios and keyboard navigation

See `DESIGN_SYSTEM.md` for complete design specifications.

---

## 📊 Performance

| Metric | Value |
|--------|-------|
| Plan Generation Time | ~15-30 seconds |
| Frontend Bundle | Optimized with Next.js 16 |
| Lighthouse Score | 90+ |
| Mobile Ready | ✅ Yes |
| Real-Time Updates | ✅ Polling with incremental rendering |

---

## 🛡️ Security

- ✅ Secure Supabase RPC functions (no public schema exposure)
- ✅ API rate limiting (Redis-based, 60s TTL)
- ✅ CORS protection for API endpoints
- ✅ Environment variables for all secrets
- ✅ Input sanitization and validation
- ✅ UUID validation for project IDs

---


## 👨‍💻 Creator

**Derril Filemon**  
*AI Engineer & Fullstack Developer*

This project demonstrates proficiency in:

- 🤖 **AI/ML Integration** — CrewAI multi-agent workflows, OpenAI GPT-4.1-mini with fine-tuned prompts
- ⚛️ **Modern React** — Next.js 16, React 19.2, App Router, Server Components
- 🐍 **Python Backend** — FastAPI, async/await, Pydantic v2, type safety
- 🎨 **UI/UX Design** — Vanilla Extract design system, responsive layouts, accessibility
- ☁️ **Cloud Architecture** — Supabase, Upstash Redis, Railway, Vercel
- 🔧 **DevOps** — CI/CD, environment management, monitoring, RPC functions
- 📱 **Mobile Development** — Mobile-first design, touch targets, bottom navigation
- 🎯 **Real-Time Features** — Polling, incremental rendering, state management

---

## 🙏 Acknowledgments

- **[CrewAI](https://www.crewai.com/)** — Multi-agent orchestration framework
- **[OpenAI](https://openai.com/)** — GPT-4.1-mini API
- **[Supabase](https://supabase.com/)** — Database & RPC functions
- **[Upstash](https://upstash.com/)** — Redis caching
- **[Railway](https://railway.app/)** — Backend deployment
- **[Vercel](https://vercel.com/)** — Frontend hosting
- **[Vanilla Extract](https://vanilla-extract.style/)** — Zero-runtime CSS-in-TS

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
