# Rodion Mayatskiy

I'm a sophomore at UAB double majoring in Computer Science and Physics. I'm heading toward AI and machine learning, and I still enjoy building for the web and making games.

I've watched 3Blue1Brown since high school, and I want to build a tool where any college student can type in a physics, math or Python problem and get an animated explanation that's actually correct, because the system solves and simulates the math instead of guessing. [Phasora](https://phasoraai.com) is my rough first version.

**Looking for a Summer 2027 software engineering or AI/ML internship.**

[Portfolio](https://rmaytr.github.io) · [LinkedIn](https://www.linkedin.com/in/rodion-mayatskiy-025128374/) · mayatrod@gmail.com

---

## At a glance

- **Research:** computational plasma physics simulations on the Cheaha supercomputer; co-author on an ML-assisted laser deposition abstract accepted for an oral presentation at AVS 72
- **Teaching:** primary TA for a 60+ student Python course; I also teach a lab section of ~40 students
- **Web:** front-end work on 1,500+ pages across 20+ UAB sites, plus production sites for two clients
- **Building:** 1st place in the EcoCAR track at HackBama_01, a multi-user Telegram bot in private beta, a local-first task planner and three multiplayer browser games
- **Leadership:** founder of The AI Collective at UAB and of Micro-Internships, now the Career Center's Project One; Events Chair of ACM at UAB
- **Academics:** 4.0 GPA, Honors College, early admission to UAB's accelerated bachelor's-to-master's program in AI

---

## Research

### Undergraduate Researcher, Computational Plasma Physics
**Dr. Renato Camata Research Group, UAB Physics** · May 2026 – Present

The group studies pulsed-laser growth of thin films, combining experiments with machine learning, AI-enhanced process control and plasma simulation. I'm 1 of 3 students on the computational team in a 12-student lab.

- Write and run coupled laser-ablation and fluid-dynamics simulations in **C** and **Basilisk** on UAB's **Cheaha supercomputer**, using Linux and Bash to manage jobs
- Work with synthetic plasma datasets (temperature and ionization fraction as ground truth), with **Python** scripts to visualize and analyze them
- Co-author of *Machine Learning-Assisted Pulsed Laser Deposition Based on Plasma Optical Emission Signatures*, accepted for an oral presentation at the **AVS 72nd International Symposium** (Pittsburgh, Nov 2026), with a co-author from Oak Ridge National Laboratory
- The study uses **Gaussian Process Bayesian Optimization** on optical emission spectra. Across 1,000 independent trials, it found optimal plasma conditions in as few as 3 adaptive iterations

### Community Data Research: TechBirmingham Partnership
**UAB PH 104** · Fall 2026

- 1 of 5 students doing applied data research on Birmingham's tech ecosystem, talent retention and program impact
- Proposed my own research question: do Birmingham employers hire tech talent from UAB, other Alabama universities or out of state?
- Completed IRB human-subjects training

---

## Projects

### [HackUAB: Physics-Verified Autonomous Racing](https://github.com/rmaytr/HackUAB)
**1st Place, EcoCAR Track, HackBama_01** · Oct 2026 · Team of 3 · My first hackathon

A self-driving race-car "brain" for CARLA and a vehicle-dynamics simulator. It sees 40 m of course, decides every 50 ms on one CPU core, and checks each plan against a physics model before driving it.

- I built the minimum-curvature racing line (least squares), the vehicle-dynamics model that checks tire grip 1.5 s ahead, ECO mode with energy analysis, the blocked-road safety fix and the web lap visualizer
- I also coordinated merges, integration and the pitch. As a team we built lidar, radar and camera sensor fusion too
- Beat the organizers' baseline on the hardest practice course: 36.8 s vs 39.5 s, with 0 cones hit instead of 4

`Python` `NumPy` `CARLA` `vehicle dynamics` `numerical optimization`

### [Cairn: Local-First Task Planner](https://github.com/rmaytr/Cairn_Task_Tracking_App)
[Live beta](https://cairn-tasks-tawny.vercel.app/) · 2026

A calm task planner for people who get overwhelmed by long lists: one-box capture, one next step, an optional AI assistant and optional end-to-end encrypted sync.

- Installable offline PWA with a dependency-aware planner and AES-GCM-256 encryption in the browser
- 846 unit and integration tests, 33 end-to-end tests

`React` `TypeScript` `Zustand` `Vite` `Supabase` `Anthropic API`

### [Canvas Assignment Tracker](https://github.com/rmaytr/CanvasAssignmentTrackingBot)
Private beta with 6 students · 2026

A multi-user Telegram bot that ranks Canvas assignments by grade weight, urgency and effort, then keeps reminding you until the work is in.

- 5,500+ lines of Python asyncio on the Canvas REST API, with per-user SQLite and Fernet-encrypted tokens
- 426 tests at 94% coverage; crash-safe, DST-correct scheduler validated with a ~28,800-tick simulation
- Runs in Docker on Google Cloud

`Python` `asyncio` `SQLite` `Docker` `Google Cloud`

### [Phasora: AI Physics Learning Platform](https://phasoraai.com)
Early stage: 2 concept pages so far · Mar 2026 – Present

A physics tutor that gives hints instead of answers and aims to reduce hallucinations in STEM explanations. The plan is to cover all of General Physics I.

`React` `Vite` `KaTeX` `Anthropic API` `Manim`

### Multiplayer Browser Games
Three real-time browser games built in Oct 2026.

- **[Pigeon Problems](https://github.com/rmaytr/Pigeon-Problems)** ([play](https://pigeon-problems.vercel.app/)): 1–4 player co-op 3D platformer with server-authoritative netcode, client-side prediction and optional WebRTC voice; 60 Hz simulation, verified under 300 ms of injected lag; 62 engine tests and 65 Playwright checks. `Three.js` `WebGL` `Cloudflare Workers` `Durable Objects`
- **[Hollow Alibi](https://github.com/rmaytr/Hollow-Alibi):** bluffing party game for 2–10 players with solo bots, WebRTC voice and an authoritative TypeScript backend. `TypeScript` `Cloudflare Workers` `D1`
- **[Raincheck Raccoons](https://github.com/rmaytr/Raincheck-Raccoons)** ([play](https://raincheck-raccoons.vercel.app)): rooftop snack-heist party game for 2–10 players with private choices and simultaneous reveals, built for the Handshake × OpenAI Multiplayer Game Challenge. `React` `TypeScript` `Cloudflare Workers` `D1`

### Client Websites
- **[BOR Realty](https://www.azrussianrealtor.com/):** see Experience below
- **[Artist Portfolio](https://sofiakamal.art):** portfolio for a Stanford painter, ceramicist, poet and photographer, with 58 works across 5 mediums and a custom "watercolor bloom" page transition. Static pre-rendering cut JavaScript from ~1,060 KB to 58 KB and raised mobile Lighthouse from 32–41 to 87–95, with 100/100 on SEO, accessibility and best practices. `React` `Node.js` `esbuild` `Python` `Puppeteer` `Vercel`

<details>
<summary><strong>Earlier and smaller projects</strong></summary>

- **Unity and Unreal Engine 5 prototypes** (Summer 2026 – present): games with physics, in progress
- **Recursion visualizer** (2026): a small Python tool I built to explain recursion to my CS 103 students
- **UE5 third-person adventure game** (2024): built in 2 weeks with C++ and Blueprints; 2nd of 30 at ASU's Game Development Camp
- **Python chess engine and Bloons TD6 automation script** (2023): early projects

</details>

---

## Experience

### Teaching Assistant, CS 103: Intro to Python
**UAB Department of Computer Science** · Aug 2026 – Present

- Appointed primary TA for a 60+ student course; I grade all homework and labs
- Teach a weekly 2-hour lab of ~40 students and hold 2 hours of office hours each week

### Web Developer Intern
**BOR Realty, LLC** · Phoenix, AZ · Summer 2026 · [azrussianrealtor.com](https://www.azrussianrealtor.com/)

- Built the brokerage's bilingual (English/Russian) site: 18 static pages in Next.js 14, React, TypeScript and Tailwind CSS
- Automated a 689-video library with the YouTube Data API v3, a Node.js sync script and a daily GitHub Actions job
- Met WCAG 2.1 AA: 0 axe-core violations across 40 audits and 300+ Playwright tests in Chrome and WebKit
- Added technical SEO and AI-search support (hreflang, sitemap, schema.org JSON-LD) and cut the hero video by 76% with ffmpeg

### Web Content Editor Student Assistant (Front-End Web Developer)
**UAB Student Affairs Marketing & Communications** · Oct 2025 – Present

- Maintain 1,500+ pages across 20+ UAB department sites in Joomla 5 with custom HTML, CSS, JavaScript and Bootstrap
- Converted a 40-page PDF annual report into an interactive, animated webpage with a 3-developer team
- Redesigned a department's video library page for cleaner organization and accessibility
- Review UAB pages for digital accessibility (WCAG/WAVE)

### Academic Peer Tutor
**UAB Vulcan Materials Academic Success Center** · Feb 2026 – May 2026

- Tutored 12+ STEM courses, including Calculus I/II, General Physics and Python
- Was the center's only General Physics I tutor and a TI-Nspire CX II specialist

---

## Leadership

- **Founder & President, The AI Collective at UAB** (Feb 2026 – Present): UAB's first interdisciplinary AI organization, with a 4-officer board, 10 founding members and 5 tracks: prompt engineering, productivity, coding and research literacy, AI ethics roundtables and industry briefings
- **Events Chair, ACM at UAB** (Aug 2026 – Present): plan and organize the year's events, including LeetCode nights, alumni panels, internship recruiting events and networking mixers
- **Micro-Internships → Project One:** proposed a program giving freshmen real project experience, then placed 10 students in 7 departments in the Spring 2026 pilot with $2,000 in department-sponsored scholarships. The Career Center made it permanent as Project One; the Fall 2026 cohort had 20 students and 18 departments
- **Website Coordinator, USGA** (Aug 2026 – Present): in charge of updating the student government website in Joomla 5 and planning its redesign

<details>
<summary><strong>More involvement</strong></summary>

- **USGA Freshman Forum** (Sep 2025 – May 2026): Member of the Year; 1 of 31 selected from 100+ applicants; co-led Career Readiness Week with a 6-student team
- **UAB Ambassador** (Apr 2026 – Present): 1 of 16 new Ambassadors selected from 140+ applicants; serve as an official student host at university events
- **International Mentor, ISSS** (Apr 2026 – Present): co-lead 3-day orientations for new international students and meet weekly with mentees
- **Member:** Women in Technology, UAB Tennis Club
- **High school:** Student Government Treasurer, eSports President & Captain, Class President for 3 years (Moscow); peer tutor in Informatics and Physics
- **Arizona Russian Theater:** actor and organizational assistant across 3 productions that helped raise $10,000

</details>

---

## Skills

| Area | Tools |
|---|---|
| **Languages** | Python, C, C++, Java, JavaScript, TypeScript, HTML, CSS, Bash |
| **AI** | Claude Code and Codex CLI (including several agents in parallel), custom skills and plugins, Anthropic API |
| **Scientific computing** | NumPy, Basilisk, Linux/HPC, CARLA, SageMath, Manim, LaTeX |
| **Web** | React, Next.js, Node.js, Vite, Tailwind CSS, esbuild, Bootstrap, Joomla 5, Vercel, GitHub Actions, technical SEO, WCAG accessibility |
| **Real-time and backend** | Three.js/WebGL, WebSockets, WebRTC, Cloudflare Workers, Python asyncio, SQLite, Supabase |
| **Cloud and DevOps** | Docker, Google Cloud, GitHub Pages |
| **Testing and performance** | pytest, Hypothesis, Vitest, Playwright, Puppeteer, axe-core, Lighthouse |
| **Game development** | Unity, Unreal Engine 5 (C++ and Blueprints) |

Much of my recent work is AI-assisted. I use Claude Code and Codex to build, often with several agents in parallel.

---

## Education

**University of Alabama at Birmingham** · Expected May 2029

B.S. in Computer Science and B.S. in Physics (Data-Driven Modeling and Technology concentration) · Minors in Mathematics and Entrepreneurship · Honors College · **4.0 GPA**, Presidential Honors List · Early admission, Accelerated Bachelor's-to-Master's Program in AI

**This semester:** Algorithms and Data Structures · Mathematical Foundations of AI · Scientific Programming · Differential Equations (Honors) · AI in a Nutshell · Community Data Research

**Completed:** Object-Oriented Programming · Discrete Structures · Calculus III · General Physics I & II · The World Through Data

<details>
<summary><strong>Awards and earlier education</strong></summary>

- 1st Place, HackBama_01, EcoCAR Track (2026)
- Freshman Forum Member of the Year (2026) and inaugural Member of the Month (Oct 2025), UAB USGA
- Presidential Honors List, UAB (2026)
- 1 of 4 first-year students selected for the Honors College SMART Leader Focus Group
- Game Development Camp, ASU: 2nd of 30 (2024)
- Ira A. Fulton Engineering Camp, ASU (2023)
- Certificate in Python Programming, Yandex Lyceum (2023)
- Prize Winner, MISIS University Olympiad in Technical & IT (2023)
- Prize Winner, All-Russian Olympiad in Technology & Languages (2021–2023)
- Award Winner, Finskills Financial Competencies Championship (2022)
- Anthropic courses: Claude 101, Claude Code 101, Claude Platform 101

**Rancho Solano Preparatory School**, Scottsdale, AZ (2023–2025): IB with HL Physics and HL Mathematics, on scholarship; 4.0 unweighted GPA, SAT 1550; Mu Alpha Theta; highest AMC 12 score at my school

</details>

---

## Outside of code

I'm working toward a pilot's license. I got to fly a small Cessna for my 18th birthday and have loved planes for as long as I can remember. I also play tennis, pickleball, table tennis and badminton, and I play a lot of flight simulators.

**Languages:** Russian (native), English (full professional), Mandarin (beginner)
