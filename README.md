# Hi, I'm Jan 👋

Junior Developer from Kraków, Poland · Applied Computer Science student at UKEN. I build backends in **Java / Spring Boot** and **Node.js**, and web and mobile apps with **TypeScript, React / Next.js and React Native**, using PostgreSQL for data.

## 🏋️ Featured project: [RepTrack](https://github.com/latemiq/reptrack)

A workout tracker with a personal-trainer panel – web app (PWA) and native Android app, built end to end on my own.

- Node.js REST API (~40 endpoints) and a PostgreSQL schema with Row Level Security
- Trainer panel: client invites via QR, workout reviews, periodized training plans
- Two-factor authentication built from scratch: passkeys (WebAuthn), TOTP, e-mail codes
- AI coach chat and importing runs from screenshots (Claude API)

**Live demo:** https://reptrack-five-tau.vercel.app

## 🚨 In progress: [Emergency Call Queue](https://github.com/latemiq/emergency-call-queue)

A Java 21 / Spring Boot backend for registering emergency calls and dispatching them to operators, built test-first.

- Call lifecycle (WAITING → ASSIGNED → IN_PROGRESS → CLOSED) modelled as an enum state machine with an exhaustive switch
- Encapsulated domain model: private constructor and a static factory method guarantee a valid initial state
- Unit tests with JUnit 5 and AssertJ, integration test with Testcontainers (PostgreSQL)

## 🛠️ Tech stack

- **Frontend:** TypeScript · JavaScript · React · Next.js · Tailwind CSS · Zustand
- **Backend:** Java 21 · Spring Boot · JUnit 5 · Maven · Node.js · REST APIs · PostgreSQL · Supabase · SQL
- **Mobile:** React Native · Expo
- **Tools:** Git · GitHub · Vercel

## 📫 Contact

dzierzkowskijan@gmail.com
