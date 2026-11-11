<div align="center">

# Enoh Uwem Akpan

### Software Engineer

I design, build, test, and maintain production web applications and APIs  
for teams that depend on them every day.

**TypeScript · React · Next.js · Node.js · PHP/Laravel**

[![Email](https://img.shields.io/badge/enohuwemakpan%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:enohuwemakpan@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/enoh-uwem-akpan-20125932a)
[![Location](https://img.shields.io/badge/Remote-Nigeria-111827?style=for-the-badge&logo=googlemaps&logoColor=white)](#get-in-touch)
[![Open to work](https://img.shields.io/badge/Open%20to%20work-Software%20Engineer-1F883D?style=for-the-badge&logo=github&logoColor=white)](#get-in-touch)

</div>

---

## About

I am a software engineer who ships full-stack features on live systems and stays with them through review, test, and release. My work sits where people actually operate: ticket workflows, operations dashboards, search, in-app notes, and the REST APIs that keep those screens honest.

Right now I am an Innovator (Software Engineer) at **eAssist Dental Solutions**, a dental-operations company whose teams run on TypeScript, React, Next.js, and Node.js. I build and update client applications and Express APIs backed by MongoDB and MySQL, wire them to authentication and real-time updates, and add the validation and logging those flows need. Pull requests land with Jest and Playwright coverage, and GitHub Actions runs those checks before merge on AWS-backed releases.

Before eAssist I was a junior full-stack developer at **Icreations Technology**, building React screens on PHP/Laravel APIs and debugging the code already in production. I am completing a **B.S. in Software Development** at BYU-Pathway Worldwide (2024–2027), and I hold the PathwayConnect Certificate (December 2024), a Web Development Certificate, and a Pilot 50 Certificate.

I like hard production bugs, clear interfaces, and a pull request that explains itself. I work remotely from Nigeria and I am open to software engineering roles where the product is real and the bar for quality is high.

---

## Skills and technologies

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![React](https://img.shields.io/badge/React-149ECA?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-111827?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-111827?style=for-the-badge&logo=express&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-0F766E?style=for-the-badge&logo=swagger&logoColor=white)

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

</div>

| | |
| --- | --- |
| **Languages** | TypeScript, JavaScript, PHP |
| **Frontend** | React, Next.js, Redux, Tailwind CSS |
| **Backend** | Node.js, Express, Laravel, REST APIs, Socket.io |
| **Data** | MongoDB, MySQL |
| **Delivery** | Git, GitHub, pull requests, Jest, Playwright, GitHub Actions, AWS |
| **How I work** | Debugging production code, automated testing, secure validation and logging, technical documentation |

---

## Projects and work

These are production systems at eAssist Dental Solutions. The repositories are private. What follows is the work I have designed, built, and shipped on them with the engineering team.

### Pearl and Opal — operations consoles

Next.js applications the operations teams live in: tickets, flows, notes, and live updates.

- Built a department stats dashboard with ticket-flow views, date ranges, status, and closing notes so leads can see what closed and why.
- Added flowchart search and guided acknowledgments, including a clear continue step, so long procedures stay searchable and confirmable.
- Reworked internal notes so the thread stays readable, new notes announce themselves, and time entry sits where people actually use it.
- Extended ticket assignment with department context, and kept the client in sync through real-time socket updates.
- Put Playwright end-to-end checks on pull requests and the test branch, and carried the apps forward through Next.js and Node upgrades.

### Oyster — the API those consoles run on

TypeScript and Express services for ticket creation, assignment, reporting, and access control, with MongoDB and MySQL behind them.

- Shipped ticket-flow queries with date-range filters, closing notes, and final documentation for closed work.
- Added sign-in filters and department options so Pearl and LeaveDesk only expose the people and roles each product should see.
- Tightened validation and logging on security-sensitive ticket creation, and kept user identity required on the create path.
- Added acknowledgment data and backfill scripts for flowchart flows, plus seed support for new-client launch workflows.
- Stood up end-to-end jobs in GitHub Actions and kept the runtime on a current Node version across environments.

### Oracle — practice operations platform

A React frontend and Node.js API deployed on AWS. Offices, tasks, notes, and executive reporting live here.

- Improved the Executive Pulse dashboard: KPI source labels, layout, and scroll behavior so leadership can read the numbers without hunting for them.
- Shipped office notes with copy-ready detail, office hours, and scanner information on the office record.
- Updated the task dashboard, including captain assignment that persists, and refined the mission-first dashboard for day-to-day use.
- Added pull-request CI so frontend changes are tested before they merge, and kept local development pointed at the right API.

### LeaveDesk — leave-of-absence workflow

An internal product for leave intake and People Services: calendars, policy checklists, and role-aware access.

- Built workflow management with automated tests covering the leave process.
- Rebranded date and state selection and updated policy workflows so staff can move a leave from intake through return.
- Added LeaveDesk login and a user filter on the Oyster API so the right people reach the right records.

### Earlier full-stack work

At **Icreations Technology** (September 2024 – February 2026) I built and maintained React features on PHP/Laravel, wrote and consumed Laravel REST APIs, and debugged existing frontend and backend code against relational data.

Alongside engineering work, I indexed historical records for Springboard with team accuracy held above 95%, and I moved a parlour’s paper financial records onto a digital system, improving tracking and update flow by more than 50%.

---

## GitHub statistics

<!-- Replace YOUR_GITHUB_USERNAME in the three image URLs below with your GitHub login. -->

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&include_all_commits=true&hide_border=true&rank_icon=percentile&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff&border_color=30363d" alt="GitHub stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&langs_count=8&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff&border_color=30363d" alt="Most used languages" />

<br />

<img src="https://streak-stats.demolab.com?user=YOUR_GITHUB_USERNAME&hide_border=true&background=0D1117&stroke=30363D&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E" alt="GitHub contribution streak" />

</div>

---

## Get in touch

I am happy to talk about a role, a codebase, or a problem worth shipping.

<div align="center">

**Enoh Uwem Akpan** · Software Engineer · Remote, Nigeria

[Email](mailto:enohuwemakpan@gmail.com) · [LinkedIn](https://www.linkedin.com/in/enoh-uwem-akpan-20125932a) · +234 902 755 4682

</div>
