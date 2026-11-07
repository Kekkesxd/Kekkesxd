
<div align="center">

# Fares Abualkheir

### Computer Engineering Student · Full-Stack Developer

📍 Istanbul, Türkiye

<img src="https://media1.tenor.com/m/xafrt118nacAAAAd/gintoki-waving-anime.gif" width="175" alt="Gintoki" />

</div>



## About Me

I'm a Computer Engineering student with experience in full-stack development and an interest in exploring different areas of software engineering.

Most of my work revolves around web development, but I've also worked on games, mobile applications, simulation software, and machine learning research.

I'm especially interested in backend and frontend development, game development, mobile development, and cybersecurity. I enjoy experimenting with different technologies and working on projects that challenge me to learn something new.


## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Frameworks & Libraries**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Databases & Tools**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Featured Projects

### 🎮 [Answer Dash](https://github.com/Kekkesxd/Answer-Dash)
`JavaScript` `HTML5 Canvas` `Node.js` `Express` `PostgreSQL` `JWT`

A neon arcade trivia game where you don't click the answer, you **run to it**. Built solo for my Computer Graphics course, then grown into a full-stack app.

- **Game engine on raw Canvas** — WASD/arrow movement, collision-based answer zones, randomized zone placement, obstacle generation with spacing rules, teleporting "reset" obstacles, particle trails, and a scanline/grid neon UI
- **Five difficulty modes**, including *Arel* (moving, shrinking answer zones) and an *Endless* leaderboard mode that ramps up obstacles and zone behaviour as rounds progress
- **5 question themes** loaded from JSON, shuffled per run, with answers reshuffled per question
- **Backend I wrote from scratch**: Express REST API in a routes → controllers → services structure, PostgreSQL leaderboard, bcrypt-hashed passwords, JWT auth in `httpOnly` cookies, protected game page, and authenticated CRUD for user-made questions
- **Tooling**: Swagger API docs, Jest unit tests, ESLint + Prettier

### 🏭 [Industrial Simulation Assistant](https://github.com/JavedanCode/industrial-simulation-assistant/tree/merging/testing)
`TypeScript` `React Native` `Expo` `REST API` `AI`

Two-person team project: a mobile app for analyzing **Arena simulation reports** and chatting with an AI about the results. You upload an Excel report, the backend parses it and computes bottleneck, queue, and throughput insights, and an LLM answers questions grounded in that data. My teammate built the backend. **I built the mobile app.**

- **Expo / React Native app** (Android, iOS, and web) with file-based routing: a report library, document upload, an analysis view, and a chat screen for each report
- **API integration** with a typed client, safe retries, error handling, and native Excel uploads, plus a configurable backend address in Settings
- **Report management**: search, rename, and delete, with local persistence implemented separately for native and web
- **Chat UX**: formatted analysis output, fewer re-renders, cached formatting, and latest replies kept in view when the keyboard opens or content resizes
- Persistent light/dark appearance settings and script-based tests for storage, formatting, and uploads

### 🧠 [Multimodal Depression Screening](https://github.com/JavedanCode/multimodal-neuropsych-detection)
`Python` `PyTorch` `scikit-learn` `Machine Learning` `Research`

University research project asking whether measuring the *quality* of audio and facial inputs improves multimodal depression screening on the E-DAIC interview dataset. I wrote the large majority of the codebase.

- **Data pipeline** that validates the dataset, decodes audio, builds acoustic and facial summaries, aligns modalities in time, and scores input quality
- **Fusion models**: equal, adaptive, and quality-conditioned fusion of audio/facial branches, plus stacking and a text-based fallback when primary inputs are missing
- **Feature selection** with Binary Harris Hawks Optimization (BHHO) and L1
- **Careful evaluation**: participant-grouped cross-validation (no person in both train and test), fold-confined preprocessing, independent verification scripts, explainability, and 18 test modules
- Results are documented honestly, including negative findings. Research only, not a clinical tool.

### 📚 [StudyHub](https://github.com/Kekkesxd/StudyHub) · [Live demo](https://studyhub-7y0p.onrender.com)
`C#` `ASP.NET Core MVC` `Entity Framework Core` `SQLite` `Docker`

Student planner built for my Web Programming course and deployed to Render with Docker.

- Registration/login with hashed passwords and session auth
- Course enrollment, assignment tracking, and a dashboard with stats
- EF Core code-first models and migrations, seeded demo data
- Dark, responsive Razor + Bootstrap UI

> Demo login: `student` / `123456`

---

## Other Projects

### 🎓 [Student Information System](https://github.com/Kekkesxd/Student-Information-System)
`Java` `Swing`

Desktop app for a Visual Programming course with **role-based access** for admins, instructors, and students, each with its own Swing panel. Handles courses, enrollments, and grades, persisted to text files through a central `DataStore`, with input validation on all forms (~2,100 lines).

### 📖 [LibManagement](https://github.com/Kekkesxd/LibManagement)
`Java` `OOP` `JUnit`

Command-line library system built around OOP design: a `Member` hierarchy with different borrowing limits, a `Searchable` interface, a generic `Paginator<T>`, late-fee calculation, CSV load/save, sortable browsing, and JUnit tests. Designed first with UML class and use-case diagrams.

---

## Beyond Programming

Outside of programming, I'm into gaming, music, photography, and spending time with friends.

I listen to pretty much every genre of music, depending on my mood, and I enjoy discovering new artists and songs.

Gaming has always been one of my main interests, whether I'm playing something competitive with friends or getting immersed in a good single-player game.

I also enjoy photography, particularly capturing interesting moments and places whenever I'm out.

And, of course, I'm into anime. Two of my favorites are **Gintama** and **One Piece**.

