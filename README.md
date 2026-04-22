# AFI – Stay Golden, Stay Connected 🟡🔵
### A Lumina Consulting Project
![WhatsApp Image 2026-02-26 at 13 01 22](https://github.com/user-attachments/assets/e16e97ab-c08b-4e30-a692-6344831f1a62)

AFI (Active Fan Interaction) is a web-based Fan Engagement Platform designed for sports fans, with a first implementation focused on Golden State Warriors supporters.

The platform transforms passive sports consumption into an interactive, community-driven digital experience that operates 365 days a year — both during the main season and off-season.

---

## 🎯 Project Context

Sports organizations face a critical and growing challenge: keeping fans engaged beyond live matches.

- During off-season, digital activity and community interaction drop significantly.
- Even in active season, most fans consume content passively (just watching scores or streams).
- There is limited real-time interaction between fans and few data-driven engagement mechanics..

AFI addresses this by providing a real-time web platform that offers **constant, interactive and community-centric experiences** all year long.

---

## 👤 Target Users

### Persona 1 – César (Busy Digital Fan)

- 25 years old, logistics coordinator.
- Passionate about sports, watches games with friends on weekends.
- Spends most of the day at the office but is always connected to the internet.

**Goals**

- Stay updated on his favorite teams without spending too much time.
- Interact with his team and support them from anywhere.

**Pain Points**

- Very little time to read long articles or browse multiple apps.
- Loses attention when the content is too long or complex.

> “I’m always up to date because I’ve already seen everything on TikTok.”

---

### Persona 2 – Valeria (Competitive Social Fan)

- 19 years old, student.
- Loves sports video games and quizzes about her favorite teams.
- Has not yet found an active community to share her passion with.

**Goals**

- Interact more with the sports community.
- Participate in games, challenges and rankings.
- Stay connected with her team all year long.

**Pain Points**

- Few interactive experiences during off-season.
- Limited diversity in games and communities.
- Most sports experiences feel repetitive and not very innovative.

> “Even when there are no matches, I want to stay connected with my team.”

---

## 🚀 Core Features

### 1. Fanatic – Weekly Guessing Game (Highlight Feature)

A weekly riddle experience:

- Guess **who**, **where** or **what** related to the team.
- One new hint every day.
- 1 attempt per day (3 attempts per week).
- The faster you guess, the more points you earn.
- Powered by semantic-embedding AI to measure how close the user’s answer is.

---

### 2. Real-Time Prediction System (Highlight Feature)

- Users predict specific events of the next match (e.g., total points, next three-pointer, quarter result).
- After the match, the system awards points based on accuracy and response time.

**Value**

- Increases live engagement during matches.
- Generates behavioral data.
- Encourages competition among fans.

---

### 3. AR Collectible Cards (Highlight Feature)

A digital collectible section where users can:

- View cards with immersive AR effects (visual movements, sounds, highlights).
- See empty slots for non-collected cards, encouraging completion.
- Track collection progress with a completion percentage.

**Value**

- Boosts long-term retention and interest.
- Creates emotional attachment to the team.
- Highly scalable for future content and sponsorships.

---

### Other Key Features

- Multi-level ranking (Bronze, Silver, Gold, Legendary).
- Daily login streak system.
- Fan of the Month stories (submit & read emotional stories from fans).
- Cosmetic store to redeem points and customize the user profile.
- Voting and idea submission for custom merchandise.
- Support for sponsored content and “key moments” interactions (e.g., big plays).

---

## 📋 Functional Requirements (Summary)

From the official specification, main functional requirements include:

- **RF1 – Registration**: users can register accounts.
- **RF2 – Real-Time Information**: live match data via external sports API.
- **RF3 – Predictions**: send predictions during matches.
- **RF4 – Points Assignment**: automatic scoring based on participation and results.
- **RF5 – User Ranking**: rankings by team and global leaderboards.
- **RF6 – Private Rooms**: friends can interact in private match rooms.
- **RF7 – Weekly Challenges**: off-season and in-season challenges to earn points.
- **RF8 – Personal Profile**: profile with points, streak and achievements.
- **RF9 – Metrics Storage**: store user behavior metrics for analysis.
- **RF10 – Login Streak**: daily login tracking and streak mechanics.
- **RF11 – Redeem Points**: spend points on cosmetics.
- **RF12 – Merchandise Customization**: submit drawings/ideas for merchandise.
- **RF13 – Merchandise Voting**: vote for the best design/product.
- **RF14 – Fan Stories**: read and submit emotional fan stories.
- **RF15 – Key Moments**: trigger interactions on key match events.
- **RF16 – Sponsored Content**: support for integrated sponsored content.
- **RF17 – Authentication**: secure authentication layer for users.

Full user stories (HU01–HU11) are documented in the project documentation and backlog.

---

## ⚙️ Non-Functional Requirements

- **RNF1 – Accessibility**: accessible from modern browsers and mobile devices (responsive design).
- **RNF2 – Latency**: live events must be updated with a latency under 2 seconds.
- **RNF3 – Adaptation**: mobile-first and responsive UI.
- **RNF4 – System Availability**: availability during live events above 90%.
- **RNF5 – Data Storage**: personal data must be securely stored following data protection regulations.
- **RNF6 – Modular System**: modular architecture to support future IA, IoT and AR features.
- **RNF8 – Backend**: Supabase must be used as the backend platform.
- **RNF9 – Programming Language**: application logic written in TypeScript.
- **RNF10 – Runtime Environment**: Node.js as the execution environment.
- **RNF11 – Frontend Framework**: React for frontend development.
- **RNF13 – Browser Compatibility**: support at least the last two versions of Chrome, Safari, Firefox and Edge.
- **RNF15 – API & WebSocket**: architecture must support REST APIs and WebSockets simultaneously.

---

## 🛠️ Tech Stack (Planned / Required)

- **Frontend**: React + TypeScript
- **Backend**: Supabase (PostgreSQL)
- **Runtime**: Node.js
- **Real-time**: WebSocket (with REST API alongside)
- **Architecture**: modular, mobile-first, cloud-friendly (TBD provider)

---

## 📊 Project Status

🟡 **Planning & Architecture Phase**

- Requirements (RF/RNF) defined.
- User personas and user stories documented.
- Low-fidelity wireframes completed.
- High-level architecture in progress.
- Product backlog active in GitHub Projects.

---

## 📂 Repository & Project Structure

This repository will contain:

- `/docs` → Architecture, requirements and additional documentation.
- `/frontend` → React + TypeScript web application.
- `/backend` → API, real-time services and integrations.
- `/assets` → Design resources (logos, palettes, images).
- `/wireframes` → Low-fidelity and future high-fidelity designs.

Associated project board (backlog):

- **AFI Backlog** – https://github.com/users/chochesanchez/projects/1

---

## 👨‍💻 Team – Lumina Consulting

- Alan Canales  
- Emily Castillo  
- Daniela Cuéllar  
- José Sánchez  
- Carolina Ortega  

---

## 🌟 Vision

AFI aims to redefine fan engagement by turning sports spectators into **active digital participants**, combining gamification, storytelling, and real-time interaction.

More than a platform.  
A digital fan identity.
