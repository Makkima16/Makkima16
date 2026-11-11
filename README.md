**English** | [Español](README.es.md)

# Andrés (Mateo) Padilla Forero

Systems Engineering student at Universidad de Caldas (expected graduation: 2028-1) · Manizales, Colombia

I focus on **applied artificial intelligence** (LLMs, RAG and computer vision) and **full stack software development**. I am looking for a **professional internship of 6 months or more**.

**Contact:** [LinkedIn](https://www.linkedin.com/in/amateopf/)

---

## About me

I like building complete systems and understanding how they work under the hood: from a robot that follows a line using only classical computer vision, to an AI tool that reads scientific literature, to a microservices platform with two-factor authentication and online payments. I have experience working in teams with branches, pull requests, automated tests and containers.

**Machine Learning and Deep Learning study group** (Universidad de Caldas, 2025): supervised and unsupervised learning, neural networks and model evaluation with Python and TensorFlow.

**Research scholar** (Universidad de Caldas, Feb. to Jul. 2025): database management, inventory and communication for a research group.

**Languages:** Spanish (native) and English (A2, in progress).

## Featured projects

### AI and data

| Project | Description | Technologies |
|---|---|---|
| [Research-Automator](https://github.com/Makkima16/Research-Automator) | AI tool (LLM + RAG) for scientific literature reviews. It generates Boolean search strings from a topic, runs them on OpenAlex, Semantic Scholar and Scopus, ranks and deduplicates the papers, and extracts structured summaries with an LLM. Search string quality was measured with a test bench and an LLM judge. | Python, SQLite, Nemotron (NVIDIA), Next.js, TypeScript |
| [RootSearch](https://github.com/Makkima16/RootSearch) | Team-built educational platform that transcribes classes and uses AI to generate summaries, quizzes, glossaries and syllabus alignment analysis. Local or cloud processing. Monorepo with CI. | NestJS, Next.js, MongoDB, Whisper, LM Studio, Docker, GitHub Actions |
| [Line_follower_VATR](https://github.com/Makkima16/Line_follower_VATR) | Line-following robot using classical computer vision (no neural networks): segmentation, PD control, state machine, junction map with depth-first search and a closed-loop simulator. | Python, OpenCV, NumPy, Bluetooth |

### Software development and architecture

| Project | Description | Technologies |
|---|---|---|
| BPM system (online courses with exams, payments and certificates) | Microservices platform: JWT authentication with two-step email verification, business logic with server-graded exams, ePayco payments and a frontend with customer and administrator roles. | See the repositories below |
| [ms-security](https://github.com/Makkima16/ms-security) | Authentication, role and permission based authorization, email 2FA, BCrypt password hashing. | Java 17, Spring Boot 3, MongoDB |
| [ms-negocio-bpm](https://github.com/Makkima16/ms-negocio-bpm) | API for courses, exams, payments, certificates and reminders, protected against unauthorized access to other users' data. | AdonisJS 5, TypeScript, MySQL |
| [ms-frontend-bpm](https://github.com/Makkima16/ms-frontend-bpm) | Web app with guards, interceptors, progressive module access and an admin panel. | Angular 18, Tailwind CSS |
| [ms-correos](https://github.com/Makkima16/ms-correos) | Email delivery service for the system. | Node.js, Python, Docker |
| [pag_soft2 (DashRoute)](https://github.com/Makkima16/pag_soft2) | Ordering and transportation platform with microservices, tests and CI. | TypeScript, Docker Compose, GitHub Actions |
| [App_notas_flutter](https://github.com/Makkima16/App_notas_flutter) and [App_Notas_Backend](https://github.com/Makkima16/App_Notas_Backend) | Mobile app for tasks, notes and reminders with its own REST API and authentication. | Flutter, Node.js, Express, MySQL, JWT |
| [Sistema_operativo (gemOS)](https://github.com/Makkima16/Sistema_operativo) | Simulated desktop operating system with a file manager, viewers, resource monitor and user accounts. | Python, CustomTkinter |

### Algorithms

| Project | Description | Technologies |
|---|---|---|
| [ADA_2026B](https://github.com/Makkima16/ADA_2026B) | Team project on two NP-hard problems: speeding up a chain of stages (0/1 knapsack with dynamic programming) and minimum audit coverage (Set Cover with a greedy algorithm and an approximation bound). My part is the Set Cover. Includes tests, evidence and a local viewer. | Python, pytest |
| [Algoritmos_2026_1](https://github.com/Makkima16/Algoritmos_2026_1) | Academic team project: two frameworks (KGeoMIP and QNodes) for the minimum information partition problem from Integrated Information Theory, with parallelism, benchmarks and a dashboard. | Python, NumPy, Numba, FastAPI, React |

## Technologies

| Area | Tools |
|---|---|
| Languages | Python, TypeScript, JavaScript, Java, Dart, SQL |
| AI and data | LLMs and RAG (Nemotron, Whisper, LM Studio), TensorFlow, OpenCV, NumPy, pandas |
| Backend | Node.js, NestJS, AdonisJS, Express, Spring Boot, REST APIs, JWT |
| Frontend and mobile | Angular, React, Next.js, Tailwind CSS, Flutter |
| Databases | MySQL, MongoDB, Oracle, SQLite |
| Tools | Git and GitHub, Docker, Docker Compose, GitHub Actions, Railway |
| Quality | pytest, Jest, Jasmine, ESLint |
| Networks and systems | Concurrent sockets, HTTP, processes and operating systems |

## Contact

If you have an internship opportunity or want to talk about any of these projects, reach out on [LinkedIn](https://www.linkedin.com/in/amateopf/).
