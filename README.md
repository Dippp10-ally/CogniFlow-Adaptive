# CogniFlow – Adaptive Learning Platform

## Overview

CogniFlow is an AI-powered adaptive learning platform designed to deliver personalized learning experiences based on individual learner performance, engagement, and mastery levels. The platform dynamically adjusts learning paths, tracks progress, and provides intelligent recommendations to improve learning outcomes.

## Features

### Learner Module

* Personalized learning dashboard
* Adaptive course recommendations
* Progress tracking and analytics
* Learning streak monitoring
* Mastery-based assessments
* Interactive learning experience

Screenshots:- 
Learner Course.png 
Learner Dashboard.png
Learner Quiz.png
Learner Users.png
Knowledgraph.png

### Admin Module

* User management
* Course management
* Learning analytics dashboard
* Content moderation
* Performance monitoring
* Platform configuration

Screenshots:- 
Admin Course.png 
Admin Dashboard.png
Admin Quiz.png
Admin Users.png

### Creator Module

* Course creation and management
* Assessment creation
* Content publishing
* Learner performance insights
* Content analytics

Screenshots:- 
Creaator Course.png 
Creator Dashboard.png
Creator Quiz.png

### Authentication & Security

* Secure authentication using Supabase Auth
* Session management
* Protected routes
* Role-based access control

## Tech Stack

### Frontend

* React
* TypeScript
* Vite
* React Router
* Tailwind CSS
* Framer Motion
* Lucide React

### Backend Services

* Supabase
* PostgreSQL Database
* Supabase Authentication
* Supabase Storage
* Supabase Realtime

### State Management & Utilities

* TanStack Query (React Query)
* Sonner Toast Notifications

## System Architecture

```text
Frontend (React + TypeScript)
            │
            ▼
     Supabase Services
     ├── Authentication
     ├── PostgreSQL Database
     ├── Storage
     └── Realtime Services
            │
            ▼
      Learning Analytics
            │
            ▼
 Adaptive Recommendation Engine
```

## Project Structure

```bash
src/
├── components/
├── pages/
│   ├── learner/
│   ├── admin/
│   └── creator/
├── layouts/
├── integrations/
│   └── supabase/
├── hooks/
├── lib/
├── data/
├── App.tsx
└── main.tsx
```

## Key Functionalities

### Adaptive Learning

The platform continuously analyzes learner interactions and performance to provide personalized learning experiences.

### Progress Monitoring

Track:

* Course completion
* Learning streaks
* Assessment scores
* Mastery levels
* Engagement metrics

### Analytics Dashboard

Provides insights into:

* Learner performance
* Course effectiveness
* Completion rates
* Engagement trends

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/cogniflow.git
cd cogniflow
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_PUBLISHABLE_KEY=your_supabase_anon_key
```

### Start Development Server

```bash
npm run dev
```

### Build Production Version

```bash
npm run build
```

## Future Enhancements

* AI-powered recommendation engine
* Learning behavior prediction
* Cognitive profile analysis
* Gamification system
* Real-time collaboration
* AI-generated quizzes
* Learning path optimization

## Author

**Anchal Koli**

B.Tech CSE (AI & ML)

## License

This project is developed for educational and research purposes.
