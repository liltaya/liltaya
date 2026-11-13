<a href="https://liltaya.github.io"><img src="assets/banner.png" width="100%" alt="Taisiia (Taya) Mamenko. Engineering Science at Simon Fraser University. Made with care, tested with rigour. Available for a full-time co-op from December 2026 to August 2027. CGPA 3.87, based in Burnaby, BC."></a>

<p align="center">
  <a href="https://liltaya.github.io"><b>Portfolio</b></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/taya-mamenko-2978b4323"><b>LinkedIn</b></a> &nbsp;·&nbsp;
  <a href="mailto:tma133@sfu.ca"><b>tma133@sfu.ca</b></a> &nbsp;·&nbsp;
  <a href="https://liltaya.github.io/Taisiia_Mamenko_Resume.pdf"><b>Résumé</b></a>
</p>

I'm Taya, an Engineering Science student at Simon Fraser University. I build developer tools and data dashboards, and with my SFU teams, robots and games. Every solo project here runs its tests in CI on every change.

**Open to:** a full-time software or engineering co-op, **December 2026 to August 2027**.

## Featured work

<a href="https://github.com/liltaya/buildscope-ai"><img src="assets/buildscope-dashboard.jpg" width="100%" alt="BuildScope dashboard with a run matrix, pipeline graph, stage failure risk, regression window, unstable tests and a benchmark chart showing a 43.6 percent slowdown."></a>

**[BuildScope](https://github.com/liltaya/buildscope-ai)** &nbsp;·&nbsp; Python, FastAPI, SQLAlchemy, SQLite, JavaScript, C++20 &nbsp;·&nbsp; *v0.1.0, November 2026*<br>
A local CI runner that keeps every attempt, test result and benchmark sample, then tells you which commit broke the build, which tests are flaky rather than broken, and which stage got slower. Inside: DAG validation, a durable job queue with leases and crash recovery, flaky-test classification, benchmark slowdown detection and a logistic-regression failure model.<br>
`706 test cases passing` `24 merged pull requests` `CI on Ubuntu and macOS`

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/liltaya/Construction-dashboard"><img src="assets/construction-dashboard.jpg" width="100%" alt="Construction Analytics Dashboard overview: budget, actual cost, variance, completion, overdue tasks and labour hours."></a><br>
      <b><a href="https://github.com/liltaya/Construction-dashboard">Construction Analytics Dashboard</a></b><br>
      C++20 · Qt6 · SQLite · CMake<br>
      Four views of budget, schedule, workforce and safety, with CSV imports validated row by row and saved all or nothing.<br>
      <code>25/25 GoogleTest</code> <code>ASan + UBSan in CI</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://liltaya.github.io/#robot"><img src="assets/stair-robot.gif" width="100%" alt="The stair-climbing robot moving its front leg linkage in the SFU engineering lab."></a><br>
      <b><a href="https://liltaya.github.io/#robot">Stair-Climbing Robot</a></b><br>
      ENSC 100 team · C++ · Raspberry Pi<br>
      A robot built to climb stairs, with its motors driven by a Raspberry Pi. I helped assemble it and wrote the C++ code for the Pi.
    </td>
  </tr>
</table>

**[Operational Data Platform & Log Analyzer](https://github.com/liltaya/Flask-service)** &nbsp;·&nbsp; Python, Flask, PostgreSQL, Docker, Nginx, Prometheus, Grafana<br>
A Flask and PostgreSQL API with health checks and metrics, deployed behind Nginx with systemd or in Docker Compose, plus a command-line analyzer that flags attacks like SQL injection and path traversal in server logs.<br>
`1,000,000 log lines in 16.2 s` `38 tests` `4 CI jobs`

**[Virus.exe](https://github.com/liltaya/virus-exe)** &nbsp;·&nbsp; C++ &nbsp;·&nbsp; *ENSC 251 team of four, in progress*<br>
A two-player strategy card game where each player defends a computer's CPU, memory, network and storage with an ordinary 52-card deck. I proposed the concept and rules, designed the class model, and wrote the Game and GameUI classes.

<sub>The software above was built, run and tested on 13 November 2026, and the screenshots come from those runs.</sub>

## Toolkit

![Python](https://img.shields.io/badge/Python-1E1915?style=flat-square&logo=python&logoColor=white)
![C++20](https://img.shields.io/badge/C%2B%2B20-1E1915?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-1E1915?style=flat-square&logo=javascript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-1E1915?style=flat-square)
![Java](https://img.shields.io/badge/Java-1E1915?style=flat-square&logo=openjdk&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-1E1915?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-1E1915?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-1E1915?style=flat-square&logo=flask&logoColor=white)
![Qt6](https://img.shields.io/badge/Qt6-1E1915?style=flat-square&logo=qt&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-1E1915?style=flat-square&logo=sqlalchemy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1E1915?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-1E1915?style=flat-square&logo=sqlite&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-1E1915?style=flat-square&logo=pytest&logoColor=white)
![GoogleTest](https://img.shields.io/badge/GoogleTest-1E1915?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1E1915?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1E1915?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-1E1915?style=flat-square&logo=linux&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-1E1915?style=flat-square&logo=raspberrypi&logoColor=white)

## How I work

- **Tested before it ships.** Tests run in CI on every change, from 25 GoogleTest cases to 706 pytest cases.
- **Checked before it is saved.** Imports are validated row by row, and bad data is rejected with a reason before it reaches a database.
- **Written down.** Architecture notes, data models and release guides live next to the code.

<sub>Burnaby, BC · Authorized to work in Canada · <a href="https://liltaya.github.io">liltaya.github.io</a></sub>
