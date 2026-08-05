<!--
  ============================================================================
  AKMAL ESMAT — GITHUB PROFILE README
  ============================================================================
  SETUP
  1. Repo must be named exactly "Akmal-Esmat" (match your GitHub username)
     with this file as README.md at the root — GitHub renders it on your
     profile page automatically.
  2. Put the /assets folder next to this file in the same repo.
  3. Every 🔧 marks something to personalize (links, usernames, wakatime).
  4. Add .github/workflows/snake.yml (below) once, then push to main.
  5. WHY EXTERNAL SVG FILES INSTEAD OF INLINE <svg>: GitHub's markdown
     sanitizer strips inline <svg>, <filter>, <feGaussianBlur>, etc. when
     pasted directly into a README — it does not render reliably. Every
     animated visual here is instead a standalone .svg file referenced via
     <img src="./assets/x.svg">, so the browser (not GitHub's sanitizer)
     renders the file directly, including its native SMIL animation.
  ============================================================================
-->

<div align="center">

<!-- ============ HERO BANNER ============ -->
<img src="./assets/hero-banner.svg" width="100%" alt="Akmal Esmat"/>

<br/>

```bash
$ whoami

Akmal Esmat
Computer & Communications Engineer — Cairo University

> DevOps Engineer @ e-finance
> Backend & Systems Builder (Spring Boot, FastAPI, .NET)
> Linux + Automation Enthusiast
> AI / Agent Systems Tinkerer
```

<!-- ============ TYPING ANIMATION ============ -->
<!-- 🔧 regenerate at https://readme-typing-svg.demolab.com -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=2600&pause=800&color=00F0FF&center=true&vCenter=true&width=700&lines=Full+Stack+Engineer;Linux+Power+User;DevOps+Engineer;Automation+Builder;AI+Agent+Developer;Backend+Engineer;Problem+Solver;Always+Learning;Shipping+Projects;Open+Source+Contributor" alt="typing animation"/>

<br/><br/>

<!-- 🔧 replace hrefs -->
<a href="https://github.com/Akmal-Esmat"><img src="https://img.shields.io/badge/GitHub-05070d?style=for-the-badge&logo=github&logoColor=00f0ff"/></a>
<a href="https://linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-05070d?style=for-the-badge&logo=linkedin&logoColor=00f0ff"/></a>
<a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-05070d?style=for-the-badge&logo=gmail&logoColor=00f0ff"/></a>

</div>

<br/>

<!-- ============ CONTRIBUTION SNAKE ============ -->
<div align="center">
<h3>Contribution Snake</h3>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Akmal-Esmat/Akmal-Esmat/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Akmal-Esmat/Akmal-Esmat/output/github-contribution-grid-snake.svg"/>
  <img src="https://raw.githubusercontent.com/Akmal-Esmat/Akmal-Esmat/output/github-contribution-grid-snake.svg" width="100%" alt="contribution snake"/>
</picture>

</div>

<details>
<summary>⚙️ snake.yml — add to <code>.github/workflows/snake.yml</code></summary>

```yaml
name: generate-snake

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:
  push:
    branches: [ main ]

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        id: snake-gif
        with:
          github_user_name: Akmal-Esmat
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

<br/>

<!-- ============ SKILLS ============ -->
<div align="center">
<h3>Stack</h3>
<img src="./assets/skills.svg" width="100%" alt="skills"/>
</div>

<br/>

<!-- ============ ARCHITECTURE ============ -->
<div align="center">
<h3>How I Build Things</h3>
<img src="./assets/architecture.svg" width="720" alt="architecture diagram"/>
<p><sub>Dots crawling down the pipe are simulated request flow — pure SVG, no JS.</sub></p>
</div>

<br/>

<!-- ============ WAKATIME (single source of truth: the anchor comment) ============ -->
<!--
  🔧 SETUP: install the WakaTime plugin in your editor, then fork
  https://github.com/anmol098/waka-readme-stats and follow its setup so a
  scheduled Action rewrites the block between the WAKATIME markers below.
  Until that Action runs once, the block stays empty — that's expected.
-->
<div align="center">
<h3>Coding Activity</h3>

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

</div>

<br/>

<!-- ============ CUSTOM STATUS WIDGETS ============ -->
<div align="center">
<table>
<tr>
<td align="center" width="20%">

**Current Focus**
```
Building AI Knowledge
Systems
```

</td>
<td align="center" width="20%">

**Learning**
```
Kubernetes
Distributed Systems
Advanced Linux
```

</td>
<td align="center" width="20%">

**Location**
```
Cairo, Egypt
```

</td>
<td align="center" width="20%">

**Status**
```
● Online
● Building
● Learning
```

</td>
<td align="center" width="20%">

**Fuel**
```
☕ 235 cups
and counting
```

</td>
</tr>
</table>
</div>

<br/>

<!-- ============ CURRENTLY BUILDING ============ -->
<div align="center">
<h3>Currently Building</h3>
<img src="./assets/building.svg" width="100%" alt="currently building"/>
</div>

<br/>

<!-- ============ FEATURED PROJECTS ============ -->
<div align="center">
<h3>Featured Projects</h3>
</div>

<table>
<tr>
<td width="50%" valign="top">

### 🐳 e-finance DevOps Handbook
Interactive reference site documenting a real DevOps internship — CI/CD design, infrastructure-as-code, and monitoring, built for future engineers to onboard from.

**Stack:** Docker · Kubernetes · Terraform · GitHub Actions · Grafana · Prometheus

🔧 [Repo](https://github.com/Akmal-Esmat/YOUR-REPO) · [Live Site](https://YOUR-LIVE-DEMO)

</td>
<td width="50%" valign="top">

### 🕵️ AI Code Checker
Tree-sitter-based pipeline that extracts structural and stylometric features from code repositories and classifies authorship signal using Random Forest / Logistic Regression / XGBoost.

**Stack:** Python · Tree-sitter · scikit-learn · XGBoost

🔧 [Repo](https://github.com/Akmal-Esmat/ai_code_checker)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔐 JWT Auth Service
Spring Boot authentication service with Spring Security, JJWT token issuance, and `BCryptPasswordEncoder` for credential hashing.

**Stack:** Java · Spring Boot · Spring Security

🔧 [Repo](https://github.com/Akmal-Esmat/YOUR-REPO)

</td>
<td width="50%" valign="top">

### 📊 UI Automation Playground
A fully simulated multi-page enterprise CI/CD platform in Streamlit — built specifically as a stable, realistic target for Selenium/Playwright practice.

**Stack:** Python · Streamlit

🔧 [Repo](https://github.com/Akmal-Esmat/YOUR-REPO)

</td>
</tr>
</table>

<br/>

<!-- ============ GITHUB ANALYTICS ============ -->
<div align="center">
<h3>Analytics</h3>

<img src="https://github-readme-stats.vercel.app/api?username=Akmal-Esmat&show_icons=true&theme=dark&bg_color=05070d&title_color=00f0ff&icon_color=7a5cff&text_color=cdd6f4&border_color=263254&count_private=true" width="49%" alt="stats"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Akmal-Esmat&theme=dark&background=05070d&stroke=263254&ring=00f0ff&fire=7a5cff&currStreakLabel=00f0ff" width="49%" alt="streak"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Akmal-Esmat&layout=compact&theme=dark&bg_color=05070d&title_color=00f0ff&text_color=cdd6f4&border_color=263254" width="100%" alt="top langs"/>

<img src="https://github-profile-trophy.vercel.app/?username=Akmal-Esmat&theme=onedark&no-frame=true&no-bg=true&margin-w=15&margin-h=15&column=7" width="100%" alt="trophies"/>

</div>

<br/>

<!-- ============ NEOFETCH-STYLE STATS CARD ============ -->
<!--
  🔧 Powered by jeantimex/neofetch-profile — https://github.com/jeantimex/neofetch-profile
  Zero setup needed: it reads your public GitHub data live from the URL below.
  Swap YOUR_USERNAME for Akmal-Esmat (already done) and it just works.
  Optional: host a config.json (see the repo's README) to customize which
  fields show and their labels/colors.
-->
<div align="center">
<h3>Neofetch</h3>

<a href="https://github.com/jeantimex/neofetch-profile">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://neofetch-profile.vercel.app/api?username=Akmal-Esmat&theme=github-dark"/>
    <img alt="Neofetch-style profile stats" src="https://neofetch-profile.vercel.app/api?username=Akmal-Esmat&theme=github-dark"/>
  </picture>
</a>

</div>

<br/>

<!-- ============ ACTIVITY GRAPH ============ -->
<div align="center">
<h3>Activity Graph</h3>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Akmal-Esmat&theme=react-dark&bg_color=05070d&color=00f0ff&line=7a5cff&point=cdd6f4&hide_border=true" width="100%" alt="activity graph"/>

</div>

<br/>

<!-- ============ PHILOSOPHY ============ -->
<div align="center">
<img src="./assets/philosophy.svg" width="900" alt="philosophy quote"/>
</div>

<br/>

<!-- ============ CONTACT ============ -->
<div align="center">
<h3>Contact</h3>

<table>
<tr>
<td align="center" width="25%">

**GitHub**
🔧 [@Akmal-Esmat](https://github.com/Akmal-Esmat)

</td>
<td align="center" width="25%">

**LinkedIn**
🔧 [Your Name](https://linkedin.com/in/YOUR-LINKEDIN)

</td>
<td align="center" width="25%">

**Portfolio**
🔧 [yoursite.dev](https://YOUR-PORTFOLIO)

</td>
<td align="center" width="25%">

**Email**
🔧 [your.email@example.com](mailto:your.email@example.com)

</td>
</tr>
</table>

<!-- 🔧 optional visitor counter -->
<!-- <img src="https://komarev.com/ghpvc/?username=Akmal-Esmat&color=00f0ff&style=flat-square&label=PROFILE+VIEWS"/> -->

</div>

<br/>

<!-- ============ EASTER EGGS (native <details> — the only real interactivity GitHub markdown allows, no JS) ============ -->
<div align="center">

<details>
<summary>👾 <code>$ sudo access --secret</code></summary>

<br/>

```
Access granted.

     _    _              _
    / \  | | ___ __ ___ | | ___
   / _ \ | |/ / '_ ` _ \| |/ _ \
  / ___ \|   <| | | | | | |  __/
 /_/   \_\_|\_\_| |_| |_|_|\___|

"The best engineers are the ones who automated
 their own job and got promoted for it."
```

🔧 swap this ASCII art / quote — generate more at
[patorjk.com/software/taag](https://patorjk.com/software/taag/).

</details>

<details>
<summary>🥚 one more thing…</summary>

<br/>

You found it. There's no prize, just the satisfaction of clicking
`<summary>` tags — which is basically a metaphor for this whole
DevOps handbook project.

</details>

</div>

<br/>

<div align="center">
<sub>🔧 Last checklist: swap every 🔧, add <code>.github/workflows/snake.yml</code>, run the waka-readme-stats Action once, delete this line.</sub>
</div>
