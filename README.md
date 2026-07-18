<div align="center">

<img src="./assets/banner.svg" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=3000&pause=1000&color=00F0FF&center=true&vCenter=true&width=800&lines=SYSTEM+ONLINE...;INITIALIZING+JUDE_JOBY_JOSEPH.exe;BUILDING+INTELLIGENT+SYSTEMS;OPEN+TO+WORK+%3A%3A+STANDBY+MODE" alt="Typing SVG" />

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=judejjj&color=00F0FF&style=for-the-badge&label=TRANSMISSIONS+RECEIVED)

</div>

<br/>

```
> whoami
```

```yaml
unit: Jude Joby Joseph
class: MCA Graduate · Software Engineer · ML Researcher
status: 🟢 ONLINE — Open to Work
deployment_targets: IT Support · Systems Admin · AI/Software Trainee
origin: Curiosity in Cybersecurity → Building Secure, Intelligent Systems
```

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="100%">
</div>

## ⚡ CURRENT DIRECTIVES

```diff
+ Building a custom audio classifier to detect environmental sound events (laughter, clapping)
+ Architecting a decentralized, always-on private cloud server for personal storage infrastructure
+ Researching automated diagnostics — co-authored "Thyroid Disease Prediction" (XGBoost) — published in IJSET
```

## 🛰️ DEPLOYED SYSTEMS

<table>
<tr>
<td width="50%">

### 🐝 HIVE Mesh Network
Decentralized hyper-local mesh grid enabling off-grid, disaster-resilient communication — built on the Android Nearby Connections API.
`Android` `Mesh Networking` `Offline-First`

</td>
<td width="50%">

### 🔒 Secure RCE Engine
Containerized online compiler executing untrusted code across 5+ languages inside isolated, auto-destructing Docker sandboxes — deployed on AWS EC2.
`Node.js` `Docker` `Flask` `AWS EC2`

</td>
</tr>
<tr>
<td width="50%">

### 🏠 DormMate
Hostel management system with a serverless AI chatbot and ML-based meal prediction engine.
`Serverless` `AI Chatbot` `ML`

</td>
<td width="50%">

### 🎓 EduMatrix
Educational management system built to unify administration across combined departments.
`Full-Stack` `Admin Systems`

</td>
</tr>
</table>

<div align="center">

[![View All Repositories](https://img.shields.io/badge/EXPLORE_ALL_SYSTEMS-00F0FF?style=for-the-badge&logo=github&logoColor=black)](https://github.com/judejjj?tab=repositories)

</div>

## 🧬 CORE ARSENAL

<div align="center">

![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=00F0FF)
![Java](https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=openjdk&logoColor=00F0FF)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=00F0FF)
![Django](https://img.shields.io/badge/Django-000000?style=for-the-badge&logo=django&logoColor=00F0FF)
![Docker](https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=00F0FF)
![Firebase](https://img.shields.io/badge/Firebase-000000?style=for-the-badge&logo=firebase&logoColor=00F0FF)
![AndroidStudio](https://img.shields.io/badge/Android_Studio-000000?style=for-the-badge&logo=androidstudio&logoColor=00F0FF)
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=00F0FF)
![Git](https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=00F0FF)

</div>

## 📡 SIGNAL TRANSMISSION LOG

<div align="center">

<img src="https://raw.githubusercontent.com/judejjj/judejjj/master/assets/metrics.svg" width="100%" />

</div>

> ⚙️ **Why this kept breaking:** the old stats widget (`github-readme-stats.vercel.app`) is a shared free service that's been unstable for months — it's a known, widespread issue, not something wrong with your setup. The fix below generates your stats as a **file stored in your own repo** instead of pinging a live third-party server every time someone visits — so it can't go down. Full YAML workflow at the bottom of this message.

## 👾 PACMAN INTERCEPT

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/judejjj/judejjj/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/judejjj/judejjj/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/judejjj/judejjj/output/pacman-contribution-graph.svg" width="100%">
</picture>

> ⚙️ **One-time setup** (the earlier repo I linked was wrong — corrected below): use **[abozanona/pacman-contribution-graph](https://github.com/abozanona/pacman-contribution-graph)**. Full YAML workflow provided at the bottom of this message.

## 🪐 3D CONTRIBUTION FIELD

<div align="center">
<img src="https://raw.githubusercontent.com/judejjj/judejjj/output/github-contribution-grid-3d-mode.svg" width="100%" />
</div>

> ⚙️ **One-time setup:** add the **[yoshi389111/github-profile-3d-contrib](https://github.com/yoshi389111/github-profile-3d-contrib)** Action — turns your contribution graph into a rotating 3D skyline. Same idea as the Pacman widget: set it up once, it updates itself forever.

## ⚙️ ONE-TIME SETUP — AUTOMATION WORKFLOWS

Everything below only needs to be done **once**. Create a repo named **exactly** `judejjj` (your username) if you haven't already, then inside it create a folder `.github/workflows/` and drop in these three files. Each one runs on a daily timer and writes its output as a file into your repo — that's what makes them immune to the "third-party server is down" problem.

**1. Pacman Intercept** → `.github/workflows/pacman.yml`
```yaml
name: Generate Pac-Man Contribution Graph
on:
  schedule:
    - cron: "0 */24 * * *"
  workflow_dispatch:
  push:
    branches: [main]
jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5
    steps:
      - name: Generate pacman-contribution-graph.svg
        uses: abozanona/pacman-contribution-graph@main
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          github_user_name: judejjj
```

**2. 3D Contribution Field** → `.github/workflows/3d-contrib.yml`
```yaml
name: 3D Contribution Graph
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
        with:
          ref: main
      - uses: yoshi389111/github-profile-3d-contrib@0.7.1
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          username: judejjj
      - name: Commit output
        run: |
          git config user.name github-actions
          git config user.email github-actions@github.com
          git add -f profile-3d-contrib || true
          git commit -m "update 3d contribution graph" || exit 0
          git push
```

**3. Signal Transmission Log (stats)** → `.github/workflows/metrics.yml`
```yaml
name: Metrics
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
jobs:
  metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.GITHUB_TOKEN }}
          user: judejjj
          filename: assets/metrics.svg
          template: classic
          base: header, activity, community, repositories
```

> Note: these are third-party open-source Actions maintained outside Anthropic — occasionally their exact input names change with new versions. If a workflow fails on first run, open the "Actions" tab in your repo, click the failed run, and check the error — it'll usually tell you exactly which parameter needs adjusting. Worth checking each project's own README on GitHub for the latest syntax before pasting.

## 🔗 OPEN CHANNELS

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=00F0FF)](https://www.linkedin.com/in/judejobyjoseph/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=00F0FF)](https://judejj.vercel.app)
[![Gmail](https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=00F0FF)](mailto:judejobyjoseph@gmail.com)

</div>

<div align="center">

```
> awaiting incoming transmission...
> connection stable // ready to collaborate
```

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%">

</div>
