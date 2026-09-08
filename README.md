# Hi, I'm Soham Panchal 👋

### Software Developer building full-stack systems across web, mobile, backend engineering, machine learning, and applied AI.

I’m a Computer Science student at the **University of Texas at Arlington** pursuing a minor in Mathematics. I like building software end to end, designing interfaces, APIs, authentication, data models, backend services, AI pipelines, and deployment infrastructure rather than stopping at a single layer.

- 🔭 **Ex Software Developer Intern at E-Sutra Technologies**
- 🧠 Interested in **software engineering, backend systems, full-stack development, mobile applications, and applied AI/ML**
- 🛠️ Comfortable moving across **frontend, backend, API, authentication, and database layers**
- 🎓 Pursuing an Honors B.S. in Computer Science with a **minor in Mathematics**, expected **May 2028**
- 📍 Based in Arlington, Texas
- 💼 Open to software engineering internships and technical collaborations

# 🛠️ Technologies

### Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![C++](https://img.shields.io/badge/C%2FC++-00599C?style=flat-square\&logo=cplusplus\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)

### Frontend & Mobile

![React](https://img.shields.io/badge/React-20232A?style=flat-square\&logo=react\&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square\&logo=react\&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square\&logo=nextdotjs\&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square\&logo=expo\&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square\&logo=android\&logoColor=white)

### Backend & APIs

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square\&logo=nodedotjs\&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square\&logo=express\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-005571?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square\&logo=jsonwebtokens\&logoColor=white)


### Databases & ORM

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square\&logo=prisma\&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square\&logo=supabase\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square\&logo=mysql\&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square\&logo=sqlite\&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square\&logo=firebase\&logoColor=black)

---

# 🚀 Featured Projects

## [CampusAI](https://github.com/SohamxP/campus-ai)

### AI-Powered Academic Productivity Platform

A full-stack academic platform that transforms uploaded course material into an interactive study system through document-grounded question answering, flashcards, quizzes, and mastery tracking.

* Built a **Next.js + TypeScript web application** supported by separate Node.js/Express and Python/FastAPI services
* Developed a complete **Retrieval-Augmented Generation pipeline** with PDF extraction, page-aware chunking, semantic embeddings, hybrid retrieval, and Cross-Encoder reranking
* Stored vector embeddings using **PostgreSQL + pgvector** and generated grounded answers using retrieved course context
* Reused indexed material across **document Q&A, flashcard generation, quiz generation, evaluation, and topic mastery tracking**
* Added automated tests covering PDF processing, embeddings, retrieval, database operations, and generation services

**Tech:** Next.js • React • TypeScript • Node.js • Express • Python • FastAPI • PostgreSQL • Supabase • pgvector • Sentence Transformers • OpenAI • Ollama

[![Live Demo](https://img.shields.io/badge/Live_Demo-Open_CampusAI-000000?style=for-the-badge\&logo=vercel\&logoColor=white)](https://campus-ai-peach.vercel.app)
[![Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge\&logo=github)](https://github.com/SohamxP/campus-ai)

---

## [RideWise](https://github.com/SohamxP/ridewise)

### ML-Powered Ride Decision Platform

A native Android application that combines traffic-aware routing, geospatial analysis, and provider-specific machine-learning models to help users compare historical ride estimates and evaluate whether to **ride now, wait, or walk to an alternate pickup point**.

* Trained separate **XGBoost regression models for Uber and Lyft** on approximately **1.5 million NYC TLC HVFHV trip records**
* Achieved **0.835 R² for Uber** and **0.894 R² for Lyft**, with median absolute errors of approximately **$2.54 and $1.77**
* Built a **FastAPI backend deployed on Google Cloud Run** for routing, taxi-zone resolution, model inference, prediction ranges, and ride-decision workflows
* Integrated **Google Routes** for traffic-aware driving and walking routes and **Google Places** for location search
* Developed **Wait & Save**, evaluating predictions at +30, +60, and +90 minutes before recommending whether waiting is worthwhile
* Developed **Walk Nearby**, evaluating alternate pickup locations through real walking routes, traffic-aware driving routes, geospatial zone resolution, and fare prediction
* Added **Firebase Authentication, Cloud Firestore trip history, provider deep links, and graceful non-NYC fallback**

**Tech:** Java • Android SDK • Python • FastAPI • XGBoost • scikit-learn • GeoPandas • Firebase • Google Routes • Google Places • Docker • Google Cloud Run

[![Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge\&logo=github)](https://github.com/SohamxP/ridewise)

> RideWise uses historical NYC TLC data and does not represent its predictions as live Uber or Lyft prices.

---

## [Hotel Management Platform](https://github.com/SohamxP/hotel-management-app)

### Production-Style Full-Stack Hotel Operations Platform

A full-stack hotel operations application covering reservations, room availability, guest management, services, billing, payments, reporting, role-based administration, operational analytics, and AI-assisted management tools.

* Built a **React Native/Expo frontend** backed by an Express/TypeScript REST API and **PostgreSQL + Prisma**
* Implemented **JWT authentication, bcrypt password hashing, persistent mobile sessions, and Manager/Front Desk role-based access control**
* Designed correct date-based room availability and reservation-overlap prevention with **transaction-safe reservation creation**
* Migrated the application's data layer from SQLite to a production-style **PostgreSQL architecture using Prisma ORM and migrations**
* Integrated **Stripe Checkout** with signature-verified webhooks and synchronized successful payments back into PostgreSQL
* Added management tools for operational insights, revenue opportunities, quality analysis, guest recovery, and optional OpenAI-powered recommendations
* Built automated backend integration tests using **Vitest + Supertest**, containerized development with **Docker**, and CI validation through **GitHub Actions**
* Deployed the backend on **Render** with production data hosted in **Supabase PostgreSQL**

**Tech:** React Native • Expo • TypeScript • Node.js • Express • PostgreSQL • Prisma • Stripe • OpenAI • Docker • GitHub Actions • Render • Supabase

[![Backend API](https://img.shields.io/badge/Production_API-Render-46E3B7?style=for-the-badge\&logo=render\&logoColor=black)](https://hotel-management-app-se81.onrender.com)
[![Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge\&logo=github)](https://github.com/SohamxP/hotel-management-app)

---

## Connect With Me

[![Portfolio](https://img.shields.io/badge/Portfolio-sohampanchal.netlify.app-111827?style=for-the-badge&logo=netlify&logoColor=white)](https://sohampanchal.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Soham_Panchal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/soham-panchal/)
[![Email](https://img.shields.io/badge/Email-work.panchalsoham%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:work.panchalsoham@gmail.com)

