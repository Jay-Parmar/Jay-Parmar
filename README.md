<div align="center">

# Hi, I'm Jay Parmar 👋

**Software Developer · New Delhi, India**

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="https://img.shields.io/badge/React_%C2%B7_APIs_%C2%B7_AWS-245C8A?style=for-the-badge" />
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=22&amp;duration=2800&amp;pause=900&amp;color=79C0FF&amp;center=true&amp;vCenter=true&amp;width=540&amp;height=42&amp;lines=React+interfaces;API+and+database+design;AWS+infrastructure+and+DevOps" />
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=22&amp;duration=2800&amp;pause=900&amp;color=0969DA&amp;center=true&amp;vCenter=true&amp;width=540&amp;height=42&amp;lines=React+interfaces;API+and+database+design;AWS+infrastructure+and+DevOps" alt="React interfaces, API and database design, AWS infrastructure and DevOps" />
</picture>

<p>
  <a href="https://www.linkedin.com/in/jayparmar789/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:jayparmar789@gmail.com"><img src="https://img.shields.io/badge/Email-B5362D?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email Jay" /></a>
  <a href="https://gitlab.com/jayparmar789"><img src="https://img.shields.io/badge/GitLab-A33A12?style=for-the-badge&amp;logo=gitlab&amp;logoColor=white" alt="GitLab" /></a>
  <a href="https://github.com/Jay-Parmar/JayParmar"><img src="https://img.shields.io/badge/Portfolio_source-30363D?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="Portfolio source" /></a>
  <img src="https://komarev.com/ghpvc/?username=Jay-Parmar&amp;style=for-the-badge&amp;color=0E75B6&amp;label=Profile+views" alt="Profile views" />
</p>

<p><a href="#selected-projects">Projects</a> · <a href="#tech-stack">Tech stack</a> · <a href="#github-activity">GitHub activity</a></p>

</div>

## About me

I'm a full-stack developer at ESSI Integrated Technologies. I build React interfaces, design APIs and database schemas, and run services on AWS.

- I load-tested a multi-server video platform with 100 operators and 70 live viewers. Moving health checks off the request path cut live-view stalls from **up to 19 seconds to about 1 second**.
- I moved releases to Docker and GitLab CI/CD for **70% faster updates** and built offline installers for sites without internet access.
- At Josh Technology Group, I built Django REST endpoints and tuned PostgreSQL queries for a recruitment platform serving **200k+ daily users**.

## Selected projects

### hirejutsu

hirejutsu ranks openings from 629 company career pages across 15 hiring systems. Its local web app shows why a job fits your résumé and lets you track your application. Python adapters feed a SQLite database. The app marks a posting closed only after a successful scan confirms it has disappeared from the company's board.

[Source](https://github.com/Jay-Parmar/hirejutsu) · [App architecture](https://github.com/Jay-Parmar/hirejutsu/blob/main/docs/app.md) · [Example daily run](https://github.com/Jay-Parmar/hirejutsu/blob/main/docs/playthrough.md)

### PocketDisco

PocketDisco is an Android alpha for listening parties. Friends can join a private room, chat, and preview audio on their own phones. FastAPI writes chat messages to PostgreSQL before publishing updates through Redis. A phone that misses a WebSocket update can recover the member list and recent chat from a versioned room snapshot.

[App and API](https://github.com/Jay-Parmar/PocketDisco/tree/feature/mobile-ui-walkthrough) · [Room protocol](https://github.com/Jay-Parmar/PocketDisco/blob/fb44e2d6edf7f3d96d4d1b86e1b251402b5c3932/docs/08-mobile-alpha.md) · [Android walkthrough (PDF)](https://github.com/Jay-Parmar/PocketDisco/blob/fb44e2d6edf7f3d96d4d1b86e1b251402b5c3932/docs/walkthrough/PocketDisco-Walkthrough.pdf)

### Hold My Files

Guests on the same Wi-Fi can download files from an Android phone using a browser and a PIN. The owner picks which folders to share. A foreground service runs the read-only Ktor server, so downloads can continue while the owner uses another app. Stopping the server invalidates every guest session and file link.

[Android MVP](https://github.com/Jay-Parmar/HoldMyFiles/tree/codex/android-mvp) · [System architecture](https://github.com/Jay-Parmar/HoldMyFiles/blob/2fbaaf4ab482be138cf5a8266ed72e94322001be/docs/architecture.md)

### ThatsMyFace

ThatsMyFace helps friends find photos of themselves after a group event. In this Android prototype, friends can opt in to share face templates derived from their selfies over Nearby Connections. Matching runs on the phone holding the photos. Friends can browse previews and request an original, which the owner approves before transfer.

[Android prototype](https://github.com/Jay-Parmar/ThatsMyFace/tree/feat/field-test-walkthrough) · [Two-phone walkthrough (PDF)](https://github.com/Jay-Parmar/ThatsMyFace/blob/1e0c3517cc6d751a8a2aa60fed8eac71c1a46349/docs/ThatsMyFace-Walkthrough.pdf)

### FoodHub Sniffer

FoodHub gives a café one order board for Zomato and Swiggy using the notifications their Android apps already send. It saves the raw events locally and rebuilds order cards from them in Kotlin. If an order ID arrives on a later update, the board links the first alert to the same card.

[Source](https://github.com/Jay-Parmar/FoodHub) · [Order grouping tests](https://github.com/Jay-Parmar/FoodHub/blob/main/app/src/test/java/com/foodhub/sniffer/OrderBoardTest.kt)

<details>
<summary>See the PocketDisco chat and ThatsMyFace gallery</summary>

<p align="center">
  <a href="https://github.com/Jay-Parmar/PocketDisco/blob/fb44e2d6edf7f3d96d4d1b86e1b251402b5c3932/docs/walkthrough/PocketDisco-Walkthrough.pdf"><img src="https://raw.githubusercontent.com/Jay-Parmar/PocketDisco/fb44e2d6edf7f3d96d4d1b86e1b251402b5c3932/docs/walkthrough/assets/room.png" height="310" alt="PocketDisco private room with two chat messages" /></a>
  <a href="https://github.com/Jay-Parmar/ThatsMyFace/blob/1e0c3517cc6d751a8a2aa60fed8eac71c1a46349/docs/ThatsMyFace-Walkthrough.pdf"><img src="https://raw.githubusercontent.com/Jay-Parmar/ThatsMyFace/1e0c3517cc6d751a8a2aa60fed8eac71c1a46349/docs/walkthrough/screenshots/grid.png" height="310" alt="ThatsMyFace test gallery with two requests awaiting the owner's approval" /></a>
</p>

</details>

## Tech stack

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&amp;logo=typescript&amp;logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Kotlin-6847BB?style=for-the-badge&amp;logo=kotlin&amp;logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&amp;logo=cplusplus&amp;logoColor=white" alt="C++" />
</p>

**Frameworks and APIs**

<p>
  <img src="https://img.shields.io/badge/React-185873?style=for-the-badge&amp;logo=react&amp;logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&amp;logo=django&amp;logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/FastAPI-00796B?style=for-the-badge&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Flask-222222?style=for-the-badge&amp;logo=flask&amp;logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/React_Native-185873?style=for-the-badge&amp;logo=react&amp;logoColor=white" alt="React Native" />
  <img src="https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge" alt="REST APIs" />
</p>

**Databases**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169A1?style=for-the-badge&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLite-17507A?style=for-the-badge&amp;logo=sqlite&amp;logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Redis-A62B26?style=for-the-badge&amp;logo=redis&amp;logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/MySQL-386883?style=for-the-badge&amp;logo=mysql&amp;logoColor=white" alt="MySQL" />
</p>

**Cloud and delivery**

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge" alt="AWS" />
  <img src="https://img.shields.io/badge/Docker-176DA5?style=for-the-badge&amp;logo=docker&amp;logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitLab_CI%2FCD-A33A12?style=for-the-badge&amp;logo=gitlab&amp;logoColor=white" alt="GitLab CI/CD" />
  <img src="https://img.shields.io/badge/Git-AF3425?style=for-the-badge&amp;logo=git&amp;logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&amp;logo=linux&amp;logoColor=black" alt="Linux" />
</p>

## GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Jay-Parmar&amp;theme=github_dark" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Jay-Parmar&amp;theme=github" alt="Jay's public repositories and contributions over the past year" width="100%" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Jay-Parmar&amp;theme=github-dark-blue&amp;hide_border=true" />
    <img src="https://streak-stats.demolab.com?user=Jay-Parmar&amp;theme=default&amp;hide_border=true" alt="Jay's total contributions, current streak, and longest streak" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Jay-Parmar&amp;theme=github-compact&amp;hide_border=true&amp;area=true" />
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=Jay-Parmar&amp;theme=github-light&amp;hide_border=true&amp;area=true" alt="Jay's daily GitHub contributions over the past month" width="100%" />
  </picture>
</p>

<details>
<summary>More stats, top languages, and trophies</summary>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Jay-Parmar&amp;show_icons=true&amp;theme=github_dark&amp;hide_border=true" />
    <img src="https://github-readme-stats.vercel.app/api?username=Jay-Parmar&amp;show_icons=true&amp;theme=default&amp;hide_border=true" alt="GitHub totals for stars, commits, pull requests, and issues" width="390" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Jay-Parmar&amp;layout=compact&amp;theme=github_dark&amp;hide_border=true" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jay-Parmar&amp;layout=compact&amp;theme=default&amp;hide_border=true" alt="Most-used languages across Jay's public repositories" width="285" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://trophy.ryglcloud.net/?username=Jay-Parmar&amp;theme=onedark&amp;no-frame=true&amp;row=1&amp;column=6" />
    <img src="https://trophy.ryglcloud.net/?username=Jay-Parmar&amp;theme=flat&amp;no-frame=true&amp;row=1&amp;column=6" alt="Jay's profile trophies for contributions and repositories" width="660" />
  </picture>
</p>

</details>

<p align="center"><em>Have a project in mind? <a href="mailto:jayparmar789@gmail.com">Get in touch.</a></em></p>
